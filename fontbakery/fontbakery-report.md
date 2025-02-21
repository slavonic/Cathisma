## FontBakery report

fontbakery version: 0.13.2





## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Cathisma-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check base characters have non-zero advance width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#base-has-width">base_has_width</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs had zero advance width:
- uniE005 (U+E005)</p>
 [code: zero-width-bases]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[19] Cathisma-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1041, but got 1020 instead</p>
 [code: ascent]



* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 260, but got 250 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#linegaps">linegaps</a></summary>
    <div>







* 🔥 **FAIL** <p>hhea lineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: hhea]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>GF_TransLatin_Arabic glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ѩ, Ѭ, ҁ, ꙁ, Ѩ, ѭ, ѫ, ꙃ, Ꙃ, Ҁ, Ѫ, Ꙁ</td>
<td align="left">cu_Cyrl (Church Slavic)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0023 (NUMBER SIGN)


- 0x0024 (DOLLAR SIGN)


- 0x0025 (PERCENT SIGN)


- 0x0026 (AMPERSAND)


- 0x002B (PLUS SIGN)


- 0x0030 (DIGIT ZERO)


- 0x0031 (DIGIT ONE)


- 0x0032 (DIGIT TWO)


- 0x0033 (DIGIT THREE)


- 0x0034 (DIGIT FOUR)


- 0x0035 (DIGIT FIVE)


- 0x0036 (DIGIT SIX)


- 0x0037 (DIGIT SEVEN)


- 0x0038 (DIGIT EIGHT)


- 0x0039 (DIGIT NINE)


- 0x003C (LESS-THAN SIGN)


- 0x003D (EQUALS SIGN)


- 0x003E (GREATER-THAN SIGN)


- 0x003F (QUESTION MARK)


- 0x0040 (COMMERCIAL AT)


- 0x0041 (LATIN CAPITAL LETTER A)


- 0x0042 (LATIN CAPITAL LETTER B)


- 0x0043 (LATIN CAPITAL LETTER C)


- 0x0044 (LATIN CAPITAL LETTER D)


- 0x0045 (LATIN CAPITAL LETTER E)


- 0x0046 (LATIN CAPITAL LETTER F)


- 0x0047 (LATIN CAPITAL LETTER G)


- 0x0048 (LATIN CAPITAL LETTER H)


- 0x0049 (LATIN CAPITAL LETTER I)


- 0x004A (LATIN CAPITAL LETTER J)


- 0x004B (LATIN CAPITAL LETTER K)


- 0x004C (LATIN CAPITAL LETTER L)


- 0x004D (LATIN CAPITAL LETTER M)


- 0x004E (LATIN CAPITAL LETTER N)


- 0x004F (LATIN CAPITAL LETTER O)


- 0x0050 (LATIN CAPITAL LETTER P)


- 0x0051 (LATIN CAPITAL LETTER Q)


- 0x0052 (LATIN CAPITAL LETTER R)


- 0x0053 (LATIN CAPITAL LETTER S)


- 0x0054 (LATIN CAPITAL LETTER T)


- 0x0055 (LATIN CAPITAL LETTER U)


- 0x0056 (LATIN CAPITAL LETTER V)


- 0x0057 (LATIN CAPITAL LETTER W)


- 0x0058 (LATIN CAPITAL LETTER X)


- 0x0059 (LATIN CAPITAL LETTER Y)


- 0x005A (LATIN CAPITAL LETTER Z)


- 0x005C (REVERSE SOLIDUS)


- 0x005E (CIRCUMFLEX ACCENT)


- 0x005F (LOW LINE)


- 0x0061 (LATIN SMALL LETTER A)


- 0x0062 (LATIN SMALL LETTER B)


- 0x0063 (LATIN SMALL LETTER C)


- 0x0064 (LATIN SMALL LETTER D)


- 0x0065 (LATIN SMALL LETTER E)


- 0x0066 (LATIN SMALL LETTER F)


- 0x0067 (LATIN SMALL LETTER G)


- 0x0068 (LATIN SMALL LETTER H)


- 0x0069 (LATIN SMALL LETTER I)


- 0x006A (LATIN SMALL LETTER J)


- 0x006B (LATIN SMALL LETTER K)


- 0x006C (LATIN SMALL LETTER L)


- 0x006D (LATIN SMALL LETTER M)


- 0x006E (LATIN SMALL LETTER N)


- 0x006F (LATIN SMALL LETTER O)


- 0x0070 (LATIN SMALL LETTER P)


- 0x0071 (LATIN SMALL LETTER Q)


- 0x0072 (LATIN SMALL LETTER R)


- 0x0073 (LATIN SMALL LETTER S)


- 0x0074 (LATIN SMALL LETTER T)


- 0x0075 (LATIN SMALL LETTER U)


- 0x0076 (LATIN SMALL LETTER V)


- 0x0077 (LATIN SMALL LETTER W)


- 0x0078 (LATIN SMALL LETTER X)


- 0x0079 (LATIN SMALL LETTER Y)


- 0x007A (LATIN SMALL LETTER Z)


- 0x007B (LEFT CURLY BRACKET)


- 0x007C (VERTICAL LINE)


- 0x007D (RIGHT CURLY BRACKET)


- 0x007E (TILDE)


- 0x00A1 (INVERTED EXCLAMATION MARK)


- 0x00A2 (CENT SIGN)


- 0x00A3 (POUND SIGN)


- 0x00A5 (YEN SIGN)


- 0x00A7 (SECTION SIGN)


- 0x00A8 (DIAERESIS)


- 0x00A9 (COPYRIGHT SIGN)


- 0x00AA (FEMININE ORDINAL INDICATOR)


- 0x00AE (REGISTERED SIGN)


- 0x00AF (MACRON)


- 0x00B0 (DEGREE SIGN)


- 0x00B4 (ACUTE ACCENT)


- 0x00B8 (CEDILLA)


- 0x00BA (MASCULINE ORDINAL INDICATOR)


- 0x00BF (INVERTED QUESTION MARK)


- 0x00C0 (LATIN CAPITAL LETTER A WITH GRAVE)


- 0x00C1 (LATIN CAPITAL LETTER A WITH ACUTE)


- 0x00C2 (LATIN CAPITAL LETTER A WITH CIRCUMFLEX)


- 0x00C3 (LATIN CAPITAL LETTER A WITH TILDE)


- 0x00C4 (LATIN CAPITAL LETTER A WITH DIAERESIS)


- 0x00C5 (LATIN CAPITAL LETTER A WITH RING ABOVE)


- 0x00C6 (LATIN CAPITAL LETTER AE)


- 0x00C7 (LATIN CAPITAL LETTER C WITH CEDILLA)


- 0x00C8 (LATIN CAPITAL LETTER E WITH GRAVE)


- 0x00C9 (LATIN CAPITAL LETTER E WITH ACUTE)


- 0x00CA (LATIN CAPITAL LETTER E WITH CIRCUMFLEX)


- 0x00CB (LATIN CAPITAL LETTER E WITH DIAERESIS)


- 0x00CC (LATIN CAPITAL LETTER I WITH GRAVE)


- 0x00CD (LATIN CAPITAL LETTER I WITH ACUTE)


- 0x00CE (LATIN CAPITAL LETTER I WITH CIRCUMFLEX)


- 0x00CF (LATIN CAPITAL LETTER I WITH DIAERESIS)


- 0x00D0 (LATIN CAPITAL LETTER ETH)


- 0x00D1 (LATIN CAPITAL LETTER N WITH TILDE)


- 0x00D2 (LATIN CAPITAL LETTER O WITH GRAVE)


- 0x00D3 (LATIN CAPITAL LETTER O WITH ACUTE)


- 0x00D4 (LATIN CAPITAL LETTER O WITH CIRCUMFLEX)


- 0x00D5 (LATIN CAPITAL LETTER O WITH TILDE)


- 0x00D6 (LATIN CAPITAL LETTER O WITH DIAERESIS)


- 0x00D7 (MULTIPLICATION SIGN)


- 0x00D8 (LATIN CAPITAL LETTER O WITH STROKE)


- 0x00D9 (LATIN CAPITAL LETTER U WITH GRAVE)


- 0x00DA (LATIN CAPITAL LETTER U WITH ACUTE)


- 0x00DB (LATIN CAPITAL LETTER U WITH CIRCUMFLEX)


- 0x00DC (LATIN CAPITAL LETTER U WITH DIAERESIS)


- 0x00DD (LATIN CAPITAL LETTER Y WITH ACUTE)


- 0x00DE (LATIN CAPITAL LETTER THORN)


- 0x00DF (LATIN SMALL LETTER SHARP S)


- 0x00E0 (LATIN SMALL LETTER A WITH GRAVE)


- 0x00E1 (LATIN SMALL LETTER A WITH ACUTE)


- 0x00E2 (LATIN SMALL LETTER A WITH CIRCUMFLEX)


- 0x00E3 (LATIN SMALL LETTER A WITH TILDE)


- 0x00E4 (LATIN SMALL LETTER A WITH DIAERESIS)


- 0x00E5 (LATIN SMALL LETTER A WITH RING ABOVE)


- 0x00E6 (LATIN SMALL LETTER AE)


- 0x00E7 (LATIN SMALL LETTER C WITH CEDILLA)


- 0x00E8 (LATIN SMALL LETTER E WITH GRAVE)


- 0x00E9 (LATIN SMALL LETTER E WITH ACUTE)


- 0x00EA (LATIN SMALL LETTER E WITH CIRCUMFLEX)


- 0x00EB (LATIN SMALL LETTER E WITH DIAERESIS)


- 0x00EC (LATIN SMALL LETTER I WITH GRAVE)


- 0x00ED (LATIN SMALL LETTER I WITH ACUTE)


- 0x00EE (LATIN SMALL LETTER I WITH CIRCUMFLEX)


- 0x00EF (LATIN SMALL LETTER I WITH DIAERESIS)


- 0x00F0 (LATIN SMALL LETTER ETH)


- 0x00F1 (LATIN SMALL LETTER N WITH TILDE)


- 0x00F2 (LATIN SMALL LETTER O WITH GRAVE)


- 0x00F3 (LATIN SMALL LETTER O WITH ACUTE)


- 0x00F4 (LATIN SMALL LETTER O WITH CIRCUMFLEX)


- 0x00F5 (LATIN SMALL LETTER O WITH TILDE)


- 0x00F6 (LATIN SMALL LETTER O WITH DIAERESIS)


- 0x00F7 (DIVISION SIGN)


- 0x00F8 (LATIN SMALL LETTER O WITH STROKE)


- 0x00F9 (LATIN SMALL LETTER U WITH GRAVE)


- 0x00FA (LATIN SMALL LETTER U WITH ACUTE)


- 0x00FB (LATIN SMALL LETTER U WITH CIRCUMFLEX)


- 0x00FC (LATIN SMALL LETTER U WITH DIAERESIS)


- 0x00FD (LATIN SMALL LETTER Y WITH ACUTE)


- 0x00FE (LATIN SMALL LETTER THORN)


- 0x00FF (LATIN SMALL LETTER Y WITH DIAERESIS)


- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


- 0x0131 (LATIN SMALL LETTER DOTLESS I)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0152 (LATIN CAPITAL LIGATURE OE)


- 0x0153 (LATIN SMALL LIGATURE OE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


- 0x0161 (LATIN SMALL LETTER S WITH CARON)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


- 0x017E (LATIN SMALL LETTER Z WITH CARON)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DA (RING ABOVE)


- 0x02DB (OGONEK)


- 0x02DC (SMALL TILDE)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x0307 (COMBINING DOT ABOVE)


- 0x030A (COMBINING RING ABOVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


- 0x2022 (BULLET)


- 0x2026 (HORIZONTAL ELLIPSIS)


- 0x2039 (SINGLE LEFT-POINTING ANGLE QUOTATION MARK)


- 0x203A (SINGLE RIGHT-POINTING ANGLE QUOTATION MARK)


- 0x20AC (EURO SIGN)


- 0x2122 (TRADE MARK SIGN)


- 0x2212 (MINUS SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure font can render its own name. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-render-own-name">googlefonts/render_own_name</a></summary>
    <div>







* 🔥 **FAIL** <p>.notdef glyphs were found when attempting to render Cathisma</p>
 [code: render-own-name]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics">googlefonts/vertical_metrics</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;90&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



* 🔥 **FAIL** <p>hhea.lineGap is &quot;90&quot; it should be 0</p>
 [code: bad-hhea.lineGap]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-spacing-marks">opentype/gdef_spacing_marks</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs seem to be spacing (because they have width &gt; 0 on the hmtx table) so they may be in the GDEF mark glyph class by mistake, or they should have zero width instead:
acutecomb (U+0301), gravecomb (U+0300), uni0311 (U+0311), uni033E (U+033E), uni0483 (U+0483), uni0486 (U+0486), uni0487 (U+0487), uni2DE1 (U+2DE1), uni2DE10487 (U+F4E1), uni2DE2 (U+2DE2), uni2DE20487 (U+F4E2), uni2DE3 (U+2DE3), uni2DE4 (U+2DE4), uni2DE5 (U+2DE5), uni2DE9 (U+2DE9), uni2DE90487 (U+F4E9), uni2DEA (U+2DEA), uni2DEA0487 (U+F4EA), uni2DEC (U+2DEC), uni2DEC0487 (U+F4EC), uni2DED (U+2DED), uni2DED0487 (U+F4ED), uni2DEF (U+2DEF), uni2DF1 (U+2DF1), uni2DF10487 (U+F4F1), uniE000 (U+E000), uniE002 (U+E002) and uniE004 (U+E004)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: .null	Contours detected: 5	Expected: 0

- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

- Glyph name: sfthyphen	Contours detected: 1	Expected: 0

- Glyph name: afii10051	Contours detected: 5	Expected: 1

- Glyph name: afii10057	Contours detected: 5	Expected: 1

- Glyph name: afii10058	Contours detected: 5	Expected: 2

- Glyph name: afii10059	Contours detected: 5	Expected: 2

- Glyph name: afii10060	Contours detected: 5	Expected: 1

- Glyph name: afii10145	Contours detected: 5	Expected: 1

- Glyph name: afii10030	Contours detected: 2	Expected: 1

- Glyph name: uni042F	Contours detected: 5	Expected: 2

- Glyph name: afii10070	Contours detected: 1	Expected: 2

- Glyph name: uni044F	Contours detected: 5	Expected: 2

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: afii10071	Contours detected: 3	Expected: 4

- Glyph name: afii10099	Contours detected: 5	Expected: 1

- Glyph name: uni0456	Contours detected: 1	Expected: 2

- Glyph name: afii10105	Contours detected: 5	Expected: 2

- Glyph name: afii10106	Contours detected: 5	Expected: 2

- Glyph name: afii10107	Contours detected: 5	Expected: 2

- Glyph name: afii10108	Contours detected: 5	Expected: 1

- Glyph name: afii10193	Contours detected: 5	Expected: 1 or 2

- Glyph name: uni0464	Contours detected: 5	Expected: 1

- Glyph name: uni0465	Contours detected: 5	Expected: 1

- Glyph name: uni046E	Contours detected: 1	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: .null	Contours detected: 5	Expected: 0

- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

- Glyph name: uni042F	Contours detected: 5	Expected: 2

- Glyph name: uni044F	Contours detected: 5	Expected: 2

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: uni0456	Contours detected: 1	Expected: 2

- Glyph name: uni0464	Contours detected: 5	Expected: 1

- Glyph name: uni0465	Contours detected: 5	Expected: 1

- Glyph name: uni046E	Contours detected: 1	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#gpos-kerning-info">gpos_kerning_info</a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+033E COMBINING VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+2027 HYPHENATION POINT: not included in any glyphset definition</li>
<li>U+2E2F VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+E000 : not included in any glyphset definition</li>
<li>U+E002 : not included in any glyphset definition</li>
<li>U+E004 : not included in any glyphset definition</li>
<li>U+E005 : not included in any glyphset definition</li>
<li>U+F4E1 : not included in any glyphset definition</li>
<li>U+F4E2 : not included in any glyphset definition</li>
<li>U+F4E9 : not included in any glyphset definition</li>
<li>U+F4EA : not included in any glyphset definition</li>
<li>U+F4EC : not included in any glyphset definition</li>
<li>U+F4ED : not included in any glyphset definition</li>
<li>U+F4F1 : not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic</code>, <code>cyrillic-ext</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: і́</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: і̀ і̆ і̏ і̑ і̾ і҃ і҆ і҇ іⷡ іⷢ іⷣ іⷤ іⷥ іⷩ іⷪ іⷬ іⷭ іⷮ іⷯ іⷱ</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-alignment-miss">outline_alignment_miss</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* afii10021 (U+0414): X=37.5,Y=700.5 (should be at cap-height 700?)

* afii10022 (U+0415): X=96.0,Y=-2.0 (should be at baseline 0?)

* afii10023 (U+0401): X=96.0,Y=-2.0 (should be at baseline 0?)

* afii10024 (U+0416): X=90.0,Y=701.0 (should be at cap-height 700?)

* afii10024 (U+0416): X=265.0,Y=701.0 (should be at cap-height 700?)

* afii10025 (U+0417): X=149.0,Y=-2.0 (should be at baseline 0?)

* afii10028 (U+041A): X=155.0,Y=701.0 (should be at cap-height 700?)

* afii10032 (U+041E): X=107.0,Y=1.0 (should be at baseline 0?)

* afii10032 (U+041E): X=138.0,Y=1.0 (should be at baseline 0?)

* afii10035 (U+0421): X=96.0,Y=-2.0 (should be at baseline 0?)

* afii10048 (U+042E): X=217.0,Y=1.0 (should be at baseline 0?)

* afii10048 (U+042E): X=248.0,Y=1.0 (should be at baseline 0?)

* afii10053 (U+0404): X=96.0,Y=-2.0 (should be at baseline 0?)

* afii10054 (U+0405): X=107.0,Y=1.0 (should be at baseline 0?)

* afii10054 (U+0405): X=138.0,Y=1.0 (should be at baseline 0?)

* afii10061 (U+040C): X=155.0,Y=701.0 (should be at cap-height 700?)

* afii10069 (U+0434): X=37.5,Y=700.5 (should be at cap-height 700?)

* afii10070 (U+0435): X=96.0,Y=-2.0 (should be at baseline 0?)

* afii10071 (U+0451): X=96.0,Y=-2.0 (should be at baseline 0?)

* afii10072 (U+0436): X=90.0,Y=701.0 (should be at cap-height 700?)

* afii10072 (U+0436): X=265.0,Y=701.0 (should be at cap-height 700?)

* afii10073 (U+0437): X=149.0,Y=-2.0 (should be at baseline 0?)

* afii10076 (U+043A): X=155.0,Y=701.0 (should be at cap-height 700?)

* afii10080 (U+043E): X=107.0,Y=1.0 (should be at baseline 0?)

* afii10080 (U+043E): X=138.0,Y=1.0 (should be at baseline 0?)

* afii10083 (U+0441): X=96.0,Y=-2.0 (should be at baseline 0?)

* afii10096 (U+044E): X=217.0,Y=1.0 (should be at baseline 0?)

* afii10096 (U+044E): X=248.0,Y=1.0 (should be at baseline 0?)

* afii10101 (U+0454): X=96.0,Y=-2.0 (should be at baseline 0?)

* afii10102 (U+0455): X=107.0,Y=1.0 (should be at baseline 0?)

* afii10102 (U+0455): X=138.0,Y=1.0 (should be at baseline 0?)

* afii10109 (U+045C): X=155.0,Y=701.0 (should be at cap-height 700?)

* asterisk (U+002A): X=235.0,Y=702.0 (should be at cap-height 700?)

* asterisk (U+002A): X=13.0,Y=702.0 (should be at cap-height 700?)

* asterisk (U+002A): X=235.0,Y=702.0 (should be at cap-height 700?)

* asterisk (U+002A): X=206.0,Y=702.0 (should be at cap-height 700?)

* asterisk (U+002A): X=43.0,Y=702.0 (should be at cap-height 700?)

* asterisk (U+002A): X=206.0,Y=702.0 (should be at cap-height 700?)

* uni0400 (U+0400): X=96.0,Y=-2.0 (should be at baseline 0?)

* uni042D (U+042D): X=162.0,Y=-2.0 (should be at baseline 0?)

* uni044D (U+044D): X=162.0,Y=-2.0 (should be at baseline 0?)

* uni0450 (U+0450): X=96.0,Y=-2.0 (should be at baseline 0?)

* uni0460 (U+0460): X=227.0,Y=0.5 (should be at baseline 0?)

* uni0460 (U+0460): X=128.5,Y=0.5 (should be at baseline 0?)

* uni0461 (U+0461): X=227.0,Y=0.5 (should be at baseline 0?)

* uni0461 (U+0461): X=128.5,Y=0.5 (should be at baseline 0?)

* uni046E (U+046E): X=149.0,Y=-2.0 (should be at baseline 0?)

* uni046F (U+046F): X=149.0,Y=-2.0 (should be at baseline 0?)

* uni0472 (U+0472): X=346.0,Y=2.0 (should be at baseline 0?)

* uni0472 (U+0472): X=343.5,Y=-1.5 (should be at baseline 0?)

* uni0472 (U+0472): X=339.0,Y=-1.0 (should be at baseline 0?)

* uni0472 (U+0472): X=16.0,Y=-1.0 (should be at baseline 0?)

* uni0472 (U+0472): X=11.5,Y=-1.5 (should be at baseline 0?)

* uni0472 (U+0472): X=9.0,Y=2.0 (should be at baseline 0?)

* uni0472 (U+0472): X=346.0,Y=2.0 (should be at baseline 0?)

* uni0472 (U+0472): X=193.0,Y=1.0 (should be at baseline 0?)

* uni0472 (U+0472): X=162.0,Y=1.0 (should be at baseline 0?)

* uni0473 (U+0473): X=346.0,Y=2.0 (should be at baseline 0?)

* uni0473 (U+0473): X=343.5,Y=-1.5 (should be at baseline 0?)

* uni0473 (U+0473): X=339.0,Y=-1.0 (should be at baseline 0?)

* uni0473 (U+0473): X=16.0,Y=-1.0 (should be at baseline 0?)

* uni0473 (U+0473): X=11.5,Y=-1.5 (should be at baseline 0?)

* uni0473 (U+0473): X=9.0,Y=2.0 (should be at baseline 0?)

* uni0473 (U+0473): X=346.0,Y=2.0 (should be at baseline 0?)

* uni0473 (U+0473): X=193.0,Y=1.0 (should be at baseline 0?)

* uni0473 (U+0473): X=162.0,Y=1.0 (should be at baseline 0?)

* uni0478 (U+0478): X=107.0,Y=1.0 (should be at baseline 0?)

* uni0478 (U+0478): X=138.0,Y=1.0 (should be at baseline 0?)

* uni0479 (U+0479): X=107.0,Y=1.0 (should be at baseline 0?)

* uni0479 (U+0479): X=138.0,Y=1.0 (should be at baseline 0?)

* uni047A (U+047A): X=186.0,Y=-1.0 (should be at baseline 0?)

* uni047A (U+047A): X=218.0,Y=1.0 (should be at baseline 0?)

* uni047A (U+047A): X=107.0,Y=1.0 (should be at baseline 0?)

* uni047A (U+047A): X=138.0,Y=-1.0 (should be at baseline 0?)

* uni047B (U+047B): X=186.0,Y=-1.0 (should be at baseline 0?)

* uni047B (U+047B): X=218.0,Y=1.0 (should be at baseline 0?)

* uni047B (U+047B): X=107.0,Y=1.0 (should be at baseline 0?)

* uni047B (U+047B): X=138.0,Y=-1.0 (should be at baseline 0?)

* uni047C (U+047C): X=227.0,Y=0.5 (should be at baseline 0?)

* uni047C (U+047C): X=128.5,Y=0.5 (should be at baseline 0?)

* uni047D (U+047D): X=227.0,Y=0.5 (should be at baseline 0?)

* uni047D (U+047D): X=128.5,Y=0.5 (should be at baseline 0?)

* uni047E (U+047E): X=227.0,Y=0.5 (should be at baseline 0?)

* uni047E (U+047E): X=128.5,Y=0.5 (should be at baseline 0?)

* uni047F (U+047F): X=227.0,Y=0.5 (should be at baseline 0?)

* uni047F (U+047F): X=128.5,Y=0.5 (should be at baseline 0?)

* uni1C82 (U+1C82): X=99.0,Y=1.0 (should be at baseline 0?)

* uni1C82 (U+1C82): X=130.0,Y=1.0 (should be at baseline 0?)

* uniA64C (U+A64C): X=227.0,Y=0.5 (should be at baseline 0?)

* uniA64C (U+A64C): X=128.5,Y=0.5 (should be at baseline 0?)

* uniA64D (U+A64D): X=227.0,Y=0.5 (should be at baseline 0?)

* uniA64D (U+A64D): X=128.5,Y=0.5 (should be at baseline 0?)

* uniA673 (U+A673): X=235.0,Y=702.0 (should be at cap-height 700?)

* uniA673 (U+A673): X=13.0,Y=702.0 (should be at cap-height 700?)

* uniA673 (U+A673): X=235.0,Y=702.0 (should be at cap-height 700?)

* uniA673 (U+A673): X=206.0,Y=702.0 (should be at cap-height 700?)

* uniA673 (U+A673): X=43.0,Y=702.0 (should be at cap-height 700?)

* uniA673 (U+A673): X=206.0,Y=702.0 (should be at cap-height 700?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* uni0474 (U+0474): L&lt;&lt;152.0,644.0&gt;--&lt;124.0,51.0&gt;&gt; -&gt; L&lt;&lt;124.0,51.0&gt;--&lt;125.0,10.0&gt;&gt;

* uni0475 (U+0475): L&lt;&lt;152.0,644.0&gt;--&lt;124.0,51.0&gt;&gt; -&gt; L&lt;&lt;124.0,51.0&gt;--&lt;125.0,10.0&gt;&gt;

* uni0476 (U+0476): L&lt;&lt;152.0,644.0&gt;--&lt;124.0,51.0&gt;&gt; -&gt; L&lt;&lt;124.0,51.0&gt;--&lt;125.0,10.0&gt;&gt;

* uni0477 (U+0477): L&lt;&lt;152.0,644.0&gt;--&lt;124.0,51.0&gt;&gt; -&gt; L&lt;&lt;124.0,51.0&gt;--&lt;125.0,10.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* afii10019 (U+0412): B&lt;&lt;114.5,480.0&gt;-&lt;114.0,480.0&gt;-&lt;114.0,481.0&gt;&gt;/B&lt;&lt;114.0,481.0&gt;-&lt;113.0,475.0&gt;-&lt;110.0,469.5&gt;&gt; = 9.462322208025613

* afii10021 (U+0414): L&lt;&lt;136.0,10.0&gt;--&lt;136.0,529.0&gt;&gt;/B&lt;&lt;136.0,529.0&gt;-&lt;130.0,501.0&gt;-&lt;122.0,479.0&gt;&gt; = 12.094757077012089

* afii10026 (U+0418): L&lt;&lt;100.0,790.0&gt;--&lt;100.0,230.0&gt;&gt;/L&lt;&lt;100.0,230.0&gt;--&lt;145.0,605.0&gt;&gt; = 6.842773412630916

* afii10026 (U+0418): L&lt;&lt;145.0,10.0&gt;--&lt;145.0,520.0&gt;&gt;/L&lt;&lt;145.0,520.0&gt;--&lt;100.0,145.0&gt;&gt; = 6.842773412630916

* afii10027 (U+0419): L&lt;&lt;100.0,790.0&gt;--&lt;100.0,230.0&gt;&gt;/L&lt;&lt;100.0,230.0&gt;--&lt;145.0,605.0&gt;&gt; = 6.842773412630916

* afii10027 (U+0419): L&lt;&lt;145.0,10.0&gt;--&lt;145.0,520.0&gt;&gt;/L&lt;&lt;145.0,520.0&gt;--&lt;100.0,145.0&gt;&gt; = 6.842773412630916

* afii10030 (U+041C): L&lt;&lt;210.0,790.0&gt;--&lt;210.0,230.0&gt;&gt;/L&lt;&lt;210.0,230.0&gt;--&lt;255.0,605.0&gt;&gt; = 6.842773412630916

* afii10030 (U+041C): L&lt;&lt;255.0,10.0&gt;--&lt;255.0,520.0&gt;&gt;/L&lt;&lt;255.0,520.0&gt;--&lt;210.0,145.0&gt;&gt; = 6.842773412630916

* afii10034 (U+0420): L&lt;&lt;100.0,787.0&gt;--&lt;100.0,370.0&gt;&gt;/B&lt;&lt;100.0,370.0&gt;-&lt;103.0,382.0&gt;-&lt;109.0,398.0&gt;&gt; = 14.036243467926457

* afii10062 (U+040E): L&lt;&lt;97.0,790.0&gt;--&lt;125.0,346.0&gt;&gt;/L&lt;&lt;125.0,346.0&gt;--&lt;145.0,715.0&gt;&gt; = 6.710895534736985

* afii10067 (U+0432): B&lt;&lt;114.5,480.0&gt;-&lt;114.0,480.0&gt;-&lt;114.0,481.0&gt;&gt;/B&lt;&lt;114.0,481.0&gt;-&lt;113.0,475.0&gt;-&lt;110.0,469.5&gt;&gt; = 9.462322208025613

* afii10069 (U+0434): L&lt;&lt;136.0,10.0&gt;--&lt;136.0,529.0&gt;&gt;/B&lt;&lt;136.0,529.0&gt;-&lt;130.0,501.0&gt;-&lt;122.0,479.0&gt;&gt; = 12.094757077012089

* afii10074 (U+0438): L&lt;&lt;100.0,790.0&gt;--&lt;100.0,230.0&gt;&gt;/L&lt;&lt;100.0,230.0&gt;--&lt;145.0,605.0&gt;&gt; = 6.842773412630916

* afii10074 (U+0438): L&lt;&lt;145.0,10.0&gt;--&lt;145.0,520.0&gt;&gt;/L&lt;&lt;145.0,520.0&gt;--&lt;100.0,145.0&gt;&gt; = 6.842773412630916

* afii10075 (U+0439): L&lt;&lt;100.0,790.0&gt;--&lt;100.0,230.0&gt;&gt;/L&lt;&lt;100.0,230.0&gt;--&lt;145.0,605.0&gt;&gt; = 6.842773412630916

* afii10075 (U+0439): L&lt;&lt;145.0,10.0&gt;--&lt;145.0,520.0&gt;&gt;/L&lt;&lt;145.0,520.0&gt;--&lt;100.0,145.0&gt;&gt; = 6.842773412630916

* afii10078 (U+043C): L&lt;&lt;210.0,790.0&gt;--&lt;210.0,230.0&gt;&gt;/L&lt;&lt;210.0,230.0&gt;--&lt;255.0,605.0&gt;&gt; = 6.842773412630916

* afii10078 (U+043C): L&lt;&lt;255.0,10.0&gt;--&lt;255.0,520.0&gt;&gt;/L&lt;&lt;255.0,520.0&gt;--&lt;210.0,145.0&gt;&gt; = 6.842773412630916

* afii10082 (U+0440): L&lt;&lt;100.0,787.0&gt;--&lt;100.0,370.0&gt;&gt;/B&lt;&lt;100.0,370.0&gt;-&lt;103.0,382.0&gt;-&lt;109.0,398.0&gt;&gt; = 14.036243467926457

* afii10110 (U+045E): L&lt;&lt;97.0,790.0&gt;--&lt;125.0,346.0&gt;&gt;/L&lt;&lt;125.0,346.0&gt;--&lt;145.0,715.0&gt;&gt; = 6.710895534736985

* uni040D (U+040D): L&lt;&lt;100.0,790.0&gt;--&lt;100.0,230.0&gt;&gt;/L&lt;&lt;100.0,230.0&gt;--&lt;145.0,605.0&gt;&gt; = 6.842773412630916

* uni040D (U+040D): L&lt;&lt;145.0,10.0&gt;--&lt;145.0,520.0&gt;&gt;/L&lt;&lt;145.0,520.0&gt;--&lt;100.0,145.0&gt;&gt; = 6.842773412630916

* uni0423 (U+0423): L&lt;&lt;97.0,790.0&gt;--&lt;125.0,346.0&gt;&gt;/L&lt;&lt;125.0,346.0&gt;--&lt;145.0,715.0&gt;&gt; = 6.710895534736985

* uni0443 (U+0443): L&lt;&lt;97.0,790.0&gt;--&lt;125.0,346.0&gt;&gt;/L&lt;&lt;125.0,346.0&gt;--&lt;145.0,715.0&gt;&gt; = 6.710895534736985

* uni045D (U+045D): L&lt;&lt;100.0,790.0&gt;--&lt;100.0,230.0&gt;&gt;/L&lt;&lt;100.0,230.0&gt;--&lt;145.0,605.0&gt;&gt; = 6.842773412630916

* uni045D (U+045D): L&lt;&lt;145.0,10.0&gt;--&lt;145.0,520.0&gt;&gt;/L&lt;&lt;145.0,520.0&gt;--&lt;100.0,145.0&gt;&gt; = 6.842773412630916

* uni0474 (U+0474): L&lt;&lt;97.0,790.0&gt;--&lt;119.0,172.0&gt;&gt;/L&lt;&lt;119.0,172.0&gt;--&lt;145.0,715.0&gt;&gt; = 4.780145210965966

* uni0475 (U+0475): L&lt;&lt;97.0,790.0&gt;--&lt;119.0,172.0&gt;&gt;/L&lt;&lt;119.0,172.0&gt;--&lt;145.0,715.0&gt;&gt; = 4.780145210965966

* uni0476 (U+0476): L&lt;&lt;97.0,790.0&gt;--&lt;119.0,172.0&gt;&gt;/L&lt;&lt;119.0,172.0&gt;--&lt;145.0,715.0&gt;&gt; = 4.780145210965966

* uni0477 (U+0477): L&lt;&lt;97.0,790.0&gt;--&lt;119.0,172.0&gt;&gt;/L&lt;&lt;119.0,172.0&gt;--&lt;145.0,715.0&gt;&gt; = 4.780145210965966

* uni0478 (U+0478): L&lt;&lt;332.0,790.0&gt;--&lt;360.0,346.0&gt;&gt;/L&lt;&lt;360.0,346.0&gt;--&lt;380.0,715.0&gt;&gt; = 6.710895534736985

* uni0479 (U+0479): L&lt;&lt;332.0,790.0&gt;--&lt;360.0,346.0&gt;&gt;/L&lt;&lt;360.0,346.0&gt;--&lt;380.0,715.0&gt;&gt; = 6.710895534736985
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID is 'PfEd', a font editor default. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: bad]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 7 | 13 | 109 | 7 | 100 | 0 | 
| 0% | 0% | 3% | 6% | 46% | 3% | 42% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
