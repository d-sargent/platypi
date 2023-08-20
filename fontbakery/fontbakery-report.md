## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[4] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure Italic styles have Roman counterparts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/family/italics_have_roman_counterparts">com.google.fonts/check/family/italics_have_roman_counterparts</a>)</summary><div>


* 🔥 **FAIL** Italics missing a Roman counterpart: fonts/ttf/Platypi_August16-Italic.ttf [code: missing-roman]
</div></details><details><summary>🔥 <b>FAIL:</b> Each font in a family must have the same set of vertical metrics values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/vertical_metrics">com.google.fonts/check/family/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** sTypoAscender is not the same across the family:
Platypi: 765
Platypi_August16 Italic: 735 [code: sTypoAscender-mismatch]
* 🔥 **FAIL** sTypoDescender is not the same across the family:
Platypi: -235
Platypi_August16 Italic: -265 [code: sTypoDescender-mismatch]
* 🔥 **FAIL** usWinAscent is not the same across the family:
Platypi: 965
Platypi_August16 Italic: 935 [code: usWinAscent-mismatch]
* 🔥 **FAIL** usWinDescent is not the same across the family:
Platypi: 235
Platypi_August16 Italic: 265 [code: usWinDescent-mismatch]
* 🔥 **FAIL** ascent is not the same across the family:
Platypi: 965
Platypi_August16 Italic: 935 [code: ascent-mismatch]
* 🔥 **FAIL** descent is not the same across the family:
Platypi: -235
Platypi_August16 Italic: -265 [code: descent-mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Verify that family names in the name table are consistent across all fonts in the family. Checks Typographic Family name (nameID 16) if present,  otherwise uses Font Family name (nameID 1) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.adobe.fonts/check/family/consistent_family_name">com.adobe.fonts/check/family/consistent_family_name</a>)</summary><div>


* 🔥 **FAIL** 2 different Font Family names were found:

* 'Platypi' was found in:
  - Platypi-Regular.ttf (nameID 1)

* 'Platypi_August16' was found in:
  - Platypi_August16-Italic.ttf (nameID 1) [code: inconsistent-family-name]
</div></details><details><summary>⚠ <b>WARN:</b> Make sure all font files have the same version value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/family/equal_font_versions">com.google.fonts/check/family/equal_font_versions</a>)</summary><div>


* ⚠ **WARN** Version info differs among font files of the same font project.
These were the version values found:
* fonts/ttf/Platypi-Regular.ttf: 0.0019989013671875
* fonts/ttf/Platypi_August16-Italic.ttf: 1.0
 [code: mismatch]
</div></details><br></div></details><details><summary><b>[19] Platypi-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/googlefonts/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00A0 (NO-BREAK SPACE)


	- 0x003A (COLON)


	- 0x2026 (HORIZONTAL ELLIPSIS)


	- 0x0021 (EXCLAMATION MARK)


	- 0x002A (ASTERISK)


	- 0x0023 (NUMBER SIGN)


	- 0x002F (SOLIDUS)


	- 0x005C (REVERSE SOLIDUS)


	- 0x0028 (LEFT PARENTHESIS)


	- 0x0029 (RIGHT PARENTHESIS)


	- 0x007B (LEFT CURLY BRACKET)


	- 0x007D (RIGHT CURLY BRACKET)


	- 0x005B (LEFT SQUARE BRACKET)


	- 0x005D (RIGHT SQUARE BRACKET)


	- 0x201C (LEFT DOUBLE QUOTATION MARK)


	- 0x201D (RIGHT DOUBLE QUOTATION MARK)


	- 0x2018 (LEFT SINGLE QUOTATION MARK)


	- 0x2019 (RIGHT SINGLE QUOTATION MARK)


	- 0x00AB (LEFT-POINTING DOUBLE ANGLE QUOTATION MARK)


	- 0x00BB (RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK)


	- 0x0022 (QUOTATION MARK)


	- 0x0027 (APOSTROPHE)


	- 0x007C (VERTICAL LINE)


	- 0x002B (PLUS SIGN)


	- 0x00D7 (MULTIPLICATION SIGN)


	- 0x00F7 (DIVISION SIGN)


	- 0x003D (EQUALS SIGN)


	- 0x003E (GREATER-THAN SIGN)


	- 0x003C (LESS-THAN SIGN)


	- 0x0025 (PERCENT SIGN)


	- 0x0308 (COMBINING DIAERESIS)


	- 0x0300 (COMBINING GRAVE ACCENT)


	- 0x0301 (COMBINING ACUTE ACCENT)


	- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


	- 0x0304 (COMBINING MACRON)


	- 0x02D9 (DOT ABOVE)


	- 0x00B0 (DEGREE SIGN)


	- 0x00C1 (LATIN CAPITAL LETTER A WITH ACUTE)


	- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


	- 0x00C2 (LATIN CAPITAL LETTER A WITH CIRCUMFLEX)


	- 0x00C4 (LATIN CAPITAL LETTER A WITH DIAERESIS)


	- 0x00C0 (LATIN CAPITAL LETTER A WITH GRAVE)


	- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


	- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


	- 0x00C5 (LATIN CAPITAL LETTER A WITH RING ABOVE)


	- 0x00C3 (LATIN CAPITAL LETTER A WITH TILDE)


	- 0x00C6 (LATIN CAPITAL LETTER AE)


	- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


	- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


	- 0x00C7 (LATIN CAPITAL LETTER C WITH CEDILLA)


	- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


	- 0x00D0 (LATIN CAPITAL LETTER ETH)


	- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


	- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


	- 0x00C9 (LATIN CAPITAL LETTER E WITH ACUTE)


	- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


	- 0x00CA (LATIN CAPITAL LETTER E WITH CIRCUMFLEX)


	- 0x00CB (LATIN CAPITAL LETTER E WITH DIAERESIS)


	- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


	- 0x00C8 (LATIN CAPITAL LETTER E WITH GRAVE)


	- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


	- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


	- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


	- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


	- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


	- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


	- 0x0132 (LATIN CAPITAL LIGATURE IJ)


	- 0x00CD (LATIN CAPITAL LETTER I WITH ACUTE)


	- 0x00CE (LATIN CAPITAL LETTER I WITH CIRCUMFLEX)


	- 0x00CF (LATIN CAPITAL LETTER I WITH DIAERESIS)


	- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


	- 0x00CC (LATIN CAPITAL LETTER I WITH GRAVE)


	- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


	- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


	- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


	- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


	- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


	- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


	- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


	- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


	- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


	- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


	- 0x00D1 (LATIN CAPITAL LETTER N WITH TILDE)


	- 0x014A (LATIN CAPITAL LETTER ENG)


	- 0x00D3 (LATIN CAPITAL LETTER O WITH ACUTE)


	- 0x00D4 (LATIN CAPITAL LETTER O WITH CIRCUMFLEX)


	- 0x00D6 (LATIN CAPITAL LETTER O WITH DIAERESIS)


	- 0x00D2 (LATIN CAPITAL LETTER O WITH GRAVE)


	- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


	- 0x014C (LATIN CAPITAL LETTER O WITH MACRON)


	- 0x00D8 (LATIN CAPITAL LETTER O WITH STROKE)


	- 0x00D5 (LATIN CAPITAL LETTER O WITH TILDE)


	- 0x0152 (LATIN CAPITAL LIGATURE OE)


	- 0x00DE (LATIN CAPITAL LETTER THORN)


	- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


	- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


	- 0x0156 (LATIN CAPITAL LETTER R WITH CEDILLA)


	- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


	- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


	- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


	- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


	- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


	- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


	- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


	- 0x00DA (LATIN CAPITAL LETTER U WITH ACUTE)


	- 0x016C (LATIN CAPITAL LETTER U WITH BREVE)


	- 0x00DB (LATIN CAPITAL LETTER U WITH CIRCUMFLEX)


	- 0x00DC (LATIN CAPITAL LETTER U WITH DIAERESIS)


	- 0x00D9 (LATIN CAPITAL LETTER U WITH GRAVE)


	- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


	- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


	- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


	- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


	- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


	- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


	- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


	- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


	- 0x00DD (LATIN CAPITAL LETTER Y WITH ACUTE)


	- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


	- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


	- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


	- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


	- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


	- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


	- 0x00E1 (LATIN SMALL LETTER A WITH ACUTE)


	- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


	- 0x00E2 (LATIN SMALL LETTER A WITH CIRCUMFLEX)


	- 0x00E4 (LATIN SMALL LETTER A WITH DIAERESIS)


	- 0x00E0 (LATIN SMALL LETTER A WITH GRAVE)


	- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


	- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


	- 0x00E5 (LATIN SMALL LETTER A WITH RING ABOVE)


	- 0x00E3 (LATIN SMALL LETTER A WITH TILDE)


	- 0x00E6 (LATIN SMALL LETTER AE)


	- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


	- 0x010D (LATIN SMALL LETTER C WITH CARON)


	- 0x00E7 (LATIN SMALL LETTER C WITH CEDILLA)


	- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


	- 0x00F0 (LATIN SMALL LETTER ETH)


	- 0x010F (LATIN SMALL LETTER D WITH CARON)


	- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


	- 0x00E9 (LATIN SMALL LETTER E WITH ACUTE)


	- 0x011B (LATIN SMALL LETTER E WITH CARON)


	- 0x00EA (LATIN SMALL LETTER E WITH CIRCUMFLEX)


	- 0x00EB (LATIN SMALL LETTER E WITH DIAERESIS)


	- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


	- 0x00E8 (LATIN SMALL LETTER E WITH GRAVE)


	- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


	- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


	- 0x011F (LATIN SMALL LETTER G WITH BREVE)


	- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


	- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


	- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


	- 0x00ED (LATIN SMALL LETTER I WITH ACUTE)


	- 0x00EE (LATIN SMALL LETTER I WITH CIRCUMFLEX)


	- 0x00EF (LATIN SMALL LETTER I WITH DIAERESIS)


	- 0x00EC (LATIN SMALL LETTER I WITH GRAVE)


	- 0x0133 (LATIN SMALL LIGATURE IJ)


	- 0x012B (LATIN SMALL LETTER I WITH MACRON)


	- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


	- 0x0237 (LATIN SMALL LETTER DOTLESS J)


	- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


	- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


	- 0x013E (LATIN SMALL LETTER L WITH CARON)


	- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


	- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


	- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


	- 0x0148 (LATIN SMALL LETTER N WITH CARON)


	- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


	- 0x00F1 (LATIN SMALL LETTER N WITH TILDE)


	- 0x014B (LATIN SMALL LETTER ENG)


	- 0x00F3 (LATIN SMALL LETTER O WITH ACUTE)


	- 0x00F4 (LATIN SMALL LETTER O WITH CIRCUMFLEX)


	- 0x00F6 (LATIN SMALL LETTER O WITH DIAERESIS)


	- 0x00F2 (LATIN SMALL LETTER O WITH GRAVE)


	- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


	- 0x014D (LATIN SMALL LETTER O WITH MACRON)


	- 0x00F8 (LATIN SMALL LETTER O WITH STROKE)


	- 0x00F5 (LATIN SMALL LETTER O WITH TILDE)


	- 0x0153 (LATIN SMALL LIGATURE OE)


	- 0x00FE (LATIN SMALL LETTER THORN)


	- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


	- 0x0159 (LATIN SMALL LETTER R WITH CARON)


	- 0x0157 (LATIN SMALL LETTER R WITH CEDILLA)


	- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


	- 0x0161 (LATIN SMALL LETTER S WITH CARON)


	- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


	- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


	- 0x00DF (LATIN SMALL LETTER SHARP S)


	- 0x0165 (LATIN SMALL LETTER T WITH CARON)


	- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


	- 0x00FA (LATIN SMALL LETTER U WITH ACUTE)


	- 0x016D (LATIN SMALL LETTER U WITH BREVE)


	- 0x00FB (LATIN SMALL LETTER U WITH CIRCUMFLEX)


	- 0x00FC (LATIN SMALL LETTER U WITH DIAERESIS)


	- 0x00F9 (LATIN SMALL LETTER U WITH GRAVE)


	- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


	- 0x016B (LATIN SMALL LETTER U WITH MACRON)


	- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


	- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


	- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


	- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


	- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


	- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


	- 0x00FD (LATIN SMALL LETTER Y WITH ACUTE)


	- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


	- 0x00FF (LATIN SMALL LETTER Y WITH DIAERESIS)


	- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


	- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


	- 0x017E (LATIN SMALL LETTER Z WITH CARON)


	- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


	- 0x00AA (FEMININE ORDINAL INDICATOR)


	- 0x00BA (MASCULINE ORDINAL INDICATOR)


	- 0x003B (SEMICOLON)


	- 0x00A1 (INVERTED EXCLAMATION MARK)


	- 0x003F (QUESTION MARK)


	- 0x00BF (INVERTED QUESTION MARK)


	- 0x00B7 (MIDDLE DOT)


	- 0x2022 (BULLET)


	- 0x2013 (EN DASH)


	- 0x2014 (EM DASH)


	- 0x005F (LOW LINE)


	- 0x201A (SINGLE LOW-9 QUOTATION MARK)


	- 0x201E (DOUBLE LOW-9 QUOTATION MARK)


	- 0x2039 (SINGLE LEFT-POINTING ANGLE QUOTATION MARK)


	- 0x203A (SINGLE RIGHT-POINTING ANGLE QUOTATION MARK)


	- 0x0040 (COMMERCIAL AT)


	- 0x0026 (AMPERSAND)


	- 0x00B6 (PILCROW SIGN)


	- 0x00A7 (SECTION SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x2122 (TRADE MARK SIGN)


	- 0x00A2 (CENT SIGN)


	- 0x0024 (DOLLAR SIGN)


	- 0x20AC (EURO SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A5 (YEN SIGN)


	- 0x2212 (MINUS SIGN)


	- 0x007E (TILDE)


	- 0x005E (CIRCUMFLEX ACCENT)


	- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


	- 0x030C (COMBINING CARON)


	- 0x0306 (COMBINING BREVE)


	- 0x030A (COMBINING RING ABOVE)


	- 0x0303 (COMBINING TILDE)


	- 0x0312 (COMBINING TURNED COMMA ABOVE)


	- 0x0326 (COMBINING COMMA BELOW)


	- 0x0327 (COMBINING CEDILLA)


	- 0x0328 (COMBINING OGONEK)


	- 0x00A8 (DIAERESIS)


	- 0x0060 (GRAVE ACCENT)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x02DC (SMALL TILDE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)
 

	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Version format is correct in 'name' table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/version_format">com.google.fonts/check/name/version_format</a>)</summary><div>


* 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000. Current version string is: "Version 0.002; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.33]" [code: bad-version-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Platypi-Regular.ttf', 'fonts/ttf/Platypi_August16-Italic.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 280, but got 235 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (765) and hhea ascent (965) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Font contains glyphs for whitespace characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphs">com.google.fonts/check/whitespace_glyphs</a>)</summary><div>


* 🔥 **FAIL** Whitespace glyph missing for codepoint 0x00A0. [code: missing-whitespace-glyph-0x00A0]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'BOLT' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: comma	Contours detected: 0	Expected: 1

	- Glyph name: hyphen	Contours detected: 0	Expected: 1

	- Glyph name: period	Contours detected: 0	Expected: 1

	- Glyph name: zero	Contours detected: 0	Expected: 2 or 3

	- Glyph name: one	Contours detected: 0	Expected: 1

	- Glyph name: two	Contours detected: 0	Expected: 1

	- Glyph name: three	Contours detected: 0	Expected: 1

	- Glyph name: four	Contours detected: 0	Expected: 1 or 2

	- Glyph name: five	Contours detected: 0	Expected: 1

	- Glyph name: six	Contours detected: 0	Expected: 1 or 2

	- Glyph name: seven	Contours detected: 0	Expected: 1

	- Glyph name: eight	Contours detected: 0	Expected: 3

	- Glyph name: nine	Contours detected: 0	Expected: 1 or 2

	- Glyph name: B	Contours detected: 0	Expected: 2 or 3

	- Glyph name: G	Contours detected: 0	Expected: 1

	- Glyph name: J	Contours detected: 0	Expected: 1

	- Glyph name: K	Contours detected: 0	Expected: 1 or 2

	- Glyph name: M	Contours detected: 0	Expected: 1

	- Glyph name: N	Contours detected: 0	Expected: 1

	- Glyph name: P	Contours detected: 0	Expected: 1 or 2

	- Glyph name: Q	Contours detected: 0	Expected: 2

	- Glyph name: R	Contours detected: 0	Expected: 1 or 2

	- Glyph name: S	Contours detected: 0	Expected: 1

	- Glyph name: U	Contours detected: 0	Expected: 1

	- Glyph name: W	Contours detected: 0	Expected: 1 or 2

	- Glyph name: X	Contours detected: 0	Expected: 1

	- Glyph name: Y	Contours detected: 0	Expected: 1

	- Glyph name: Z	Contours detected: 0	Expected: 1

	- Glyph name: b	Contours detected: 0	Expected: 2

	- Glyph name: f	Contours detected: 0	Expected: 1

	- Glyph name: j	Contours detected: 0	Expected: 2

	- Glyph name: k	Contours detected: 0	Expected: 1 or 2

	- Glyph name: q	Contours detected: 0	Expected: 2

	- Glyph name: r	Contours detected: 0	Expected: 1

	- Glyph name: s	Contours detected: 0	Expected: 1

	- Glyph name: t	Contours detected: 0	Expected: 1

	- Glyph name: w	Contours detected: 0	Expected: 1

	- Glyph name: x	Contours detected: 0	Expected: 1

	- Glyph name: y	Contours detected: 0	Expected: 1

	- Glyph name: z	Contours detected: 0	Expected: 1

	- Glyph name: B	Contours detected: 0	Expected: 2 or 3

	- Glyph name: G	Contours detected: 0	Expected: 1

	- Glyph name: J	Contours detected: 0	Expected: 1

	- Glyph name: K	Contours detected: 0	Expected: 1 or 2

	- Glyph name: M	Contours detected: 0	Expected: 1

	- Glyph name: N	Contours detected: 0	Expected: 1

	- Glyph name: P	Contours detected: 0	Expected: 1 or 2

	- Glyph name: Q	Contours detected: 0	Expected: 2

	- Glyph name: R	Contours detected: 0	Expected: 1 or 2

	- Glyph name: S	Contours detected: 0	Expected: 1

	- Glyph name: U	Contours detected: 0	Expected: 1

	- Glyph name: W	Contours detected: 0	Expected: 1 or 2

	- Glyph name: X	Contours detected: 0	Expected: 1

	- Glyph name: Y	Contours detected: 0	Expected: 1

	- Glyph name: Z	Contours detected: 0	Expected: 1

	- Glyph name: b	Contours detected: 0	Expected: 2

	- Glyph name: comma	Contours detected: 0	Expected: 1

	- Glyph name: eight	Contours detected: 0	Expected: 3

	- Glyph name: f	Contours detected: 0	Expected: 1

	- Glyph name: five	Contours detected: 0	Expected: 1

	- Glyph name: four	Contours detected: 0	Expected: 1 or 2

	- Glyph name: hyphen	Contours detected: 0	Expected: 1

	- Glyph name: j	Contours detected: 0	Expected: 2

	- Glyph name: k	Contours detected: 0	Expected: 1 or 2

	- Glyph name: nine	Contours detected: 0	Expected: 1 or 2

	- Glyph name: one	Contours detected: 0	Expected: 1

	- Glyph name: period	Contours detected: 0	Expected: 1

	- Glyph name: q	Contours detected: 0	Expected: 2

	- Glyph name: r	Contours detected: 0	Expected: 1

	- Glyph name: s	Contours detected: 0	Expected: 1

	- Glyph name: seven	Contours detected: 0	Expected: 1

	- Glyph name: six	Contours detected: 0	Expected: 1 or 2

	- Glyph name: t	Contours detected: 0	Expected: 1

	- Glyph name: three	Contours detected: 0	Expected: 1

	- Glyph name: two	Contours detected: 0	Expected: 1

	- Glyph name: w	Contours detected: 0	Expected: 1

	- Glyph name: x	Contours detected: 0	Expected: 1

	- Glyph name: y	Contours detected: 0	Expected: 1

	- Glyph name: z	Contours detected: 0	Expected: 1 

	- Glyph name: zero	Contours detected: 0	Expected: 2 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters should disappear in other cases, for example: i̇ j̇ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* C (U+0043): X=533.0,Y=688.5 (should be at cap-height 690?)

	* d (U+0064): X=335.0,Y=688.0 (should be at cap-height 690?)

	* h (U+0068): X=31.0,Y=688.0 (should be at cap-height 690?) 

	* l (U+006C): X=31.0,Y=688.0 (should be at cap-height 690?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* A (U+0041) contains a short segment L<<2.0,0.0>--<2.0,16.0>>

	* A (U+0041) contains a short segment L<<217.0,674.0>--<217.0,690.0>>

	* A (U+0041) contains a short segment L<<711.0,16.0>--<711.0,0.0>>

	* A (U+0041) contains a short segment L<<443.0,0.0>--<443.0,16.0>>

	* A (U+0041) contains a short segment L<<244.0,16.0>--<244.0,0.0>>

	* C (U+0043) contains a short segment L<<581.0,512.0>--<565.0,512.0>>

	* E (U+0045) contains a short segment L<<42.0,0.0>--<42.0,16.0>>

	* E (U+0045) contains a short segment L<<42.0,674.0>--<42.0,690.0>>

	* E (U+0045) contains a short segment L<<553.0,696.0>--<564.0,696.0>>

	* E (U+0045) contains a short segment L<<571.0,533.0>--<555.0,533.0>>

	* E (U+0045) contains a short segment L<<468.0,461.0>--<484.0,461.0>>

	* E (U+0045) contains a short segment L<<474.0,247.0>--<458.0,247.0>>

	* E (U+0045) contains a short segment L<<571.0,182.0>--<587.0,182.0>>

	* F (U+0046) contains a short segment L<<42.0,0.0>--<42.0,16.0>>

	* F (U+0046) contains a short segment L<<42.0,674.0>--<42.0,690.0>>

	* F (U+0046) contains a short segment L<<543.0,696.0>--<554.0,696.0>>

	* F (U+0046) contains a short segment L<<561.0,533.0>--<545.0,533.0>>

	* F (U+0046) contains a short segment L<<458.0,441.0>--<474.0,441.0>>

	* F (U+0046) contains a short segment L<<464.0,227.0>--<448.0,227.0>>

	* F (U+0046) contains a short segment L<<315.0,16.0>--<315.0,0.0>>

	* H (U+0048) contains a short segment L<<42.0,0.0>--<42.0,16.0>>

	* H (U+0048) contains a short segment L<<42.0,674.0>--<42.0,690.0>>

	* H (U+0048) contains a short segment L<<289.0,690.0>--<289.0,674.0>>

	* H (U+0048) contains a short segment L<<500.0,674.0>--<500.0,690.0>>

	* H (U+0048) contains a short segment L<<748.0,690.0>--<748.0,674.0>>

	* H (U+0048) contains a short segment L<<748.0,16.0>--<748.0,0.0>>

	* H (U+0048) contains a short segment L<<500.0,0.0>--<500.0,16.0>>

	* H (U+0048) contains a short segment L<<289.0,16.0>--<289.0,0.0>>

	* L (U+004C) contains a short segment L<<42.0,0.0>--<42.0,16.0>>

	* L (U+004C) contains a short segment L<<42.0,674.0>--<42.0,690.0>>

	* L (U+004C) contains a short segment L<<290.0,690.0>--<290.0,674.0>>

	* L (U+004C) contains a short segment L<<540.0,194.0>--<556.0,194.0>>

	* T (U+0054) contains a short segment L<<230.0,0.0>--<230.0,16.0>>

	* T (U+0054) contains a short segment L<<71.0,523.0>--<55.0,523.0>>

	* T (U+0054) contains a short segment L<<42.0,696.0>--<53.0,696.0>>

	* T (U+0054) contains a short segment L<<655.0,696.0>--<666.0,696.0>>

	* T (U+0054) contains a short segment L<<653.0,523.0>--<637.0,523.0>>

	* T (U+0054) contains a short segment L<<477.0,16.0>--<477.0,0.0>>

	* V (U+0056) contains a short segment L<<682.0,690.0>--<682.0,674.0>>

	* V (U+0056) contains a short segment L<<2.0,674.0>--<2.0,690.0>>

	* V (U+0056) contains a short segment L<<270.0,690.0>--<270.0,674.0>>

	* V (U+0056) contains a short segment L<<440.0,674.0>--<440.0,690.0>>

	* a (U+0061) contains a short segment L<<375.0,79.0>--<366.0,79.0>>

	* d (U+0064) contains a short segment L<<410.0,467.0>--<410.0,467.0>>

	* d (U+0064) contains a short segment L<<410.0,467.0>--<415.0,467.0>>

	* d (U+0064) contains a short segment L<<335.0,688.0>--<335.0,703.0>>

	* d (U+0064) contains a short segment L<<562.0,68.0>--<562.0,53.0>>

	* d (U+0064) contains a short segment L<<419.0,79.0>--<410.0,79.0>>

	* g (U+0067) contains a short segment L<<423.0,601.0>--<430.0,601.0>>

	* g (U+0067) contains a short segment L<<514.0,527.0>--<514.0,515.0>>

	* g (U+0067) contains a short segment L<<390.0,463.0>--<390.0,460.0>>

	* h (U+0068) contains a short segment L<<30.0,0.0>--<30.0,14.0>>

	* h (U+0068) contains a short segment L<<31.0,688.0>--<31.0,703.0>>

	* h (U+0068) contains a short segment L<<183.0,401.0>--<192.0,401.0>>

	* h (U+0068) contains a short segment L<<616.0,14.0>--<616.0,0.0>>

	* h (U+0068) contains a short segment L<<379.0,0.0>--<379.0,14.0>>

	* h (U+0068) contains a short segment L<<268.0,14.0>--<268.0,0.0>>

	* m (U+006D) contains a short segment L<<30.0,0.0>--<30.0,14.0>>

	* m (U+006D) contains a short segment L<<31.0,407.0>--<31.0,422.0>>

	* m (U+006D) contains a short segment L<<167.0,484.0>--<189.0,484.0>>

	* m (U+006D) contains a short segment L<<183.0,401.0>--<192.0,401.0>>

	* m (U+006D) contains a short segment L<<925.0,14.0>--<925.0,0.0>>

	* m (U+006D) contains a short segment L<<688.0,0.0>--<688.0,14.0>>

	* m (U+006D) contains a short segment L<<596.0,14.0>--<596.0,0.0>>

	* m (U+006D) contains a short segment L<<359.0,0.0>--<359.0,14.0>>

	* m (U+006D) contains a short segment L<<268.0,14.0>--<268.0,0.0>>

	* n (U+006E) contains a short segment L<<30.0,0.0>--<30.0,14.0>>

	* n (U+006E) contains a short segment L<<31.0,407.0>--<31.0,422.0>>

	* n (U+006E) contains a short segment L<<183.0,401.0>--<192.0,401.0>>

	* n (U+006E) contains a short segment L<<616.0,14.0>--<616.0,0.0>>

	* n (U+006E) contains a short segment L<<379.0,0.0>--<379.0,14.0>>

	* n (U+006E) contains a short segment L<<268.0,14.0>--<268.0,0.0>>

	* p (U+0070) contains a short segment L<<30.0,-235.0>--<30.0,-221.0>>

	* p (U+0070) contains a short segment L<<31.0,407.0>--<31.0,422.0>>

	* p (U+0070) contains a short segment L<<183.0,401.0>--<192.0,401.0>>

	* p (U+0070) contains a short segment L<<192.0,13.0>--<192.0,13.0>>

	* p (U+0070) contains a short segment L<<192.0,13.0>--<188.0,13.0>>

	* p (U+0070) contains a short segment L<<288.0,-221.0>--<288.0,-235.0>>

	* u (U+0075) contains a short segment L<<443.0,79.0>--<434.0,79.0>>

	* u (U+0075) contains a short segment L<<30.0,413.0>--<30.0,428.0>>

	* u (U+0075) contains a short segment L<<359.0,413.0>--<359.0,428.0>>

	* u (U+0075) contains a short segment L<<586.0,68.0>--<586.0,53.0>>

	* v (U+0076) contains a short segment L<<2.0,466.0>--<2.0,480.0>>

	* v (U+0076) contains a short segment L<<225.0,480.0>--<225.0,466.0>>

	* v (U+0076) contains a short segment L<<331.0,466.0>--<331.0,480.0>> 

	* v (U+0076) contains a short segment L<<520.0,480.0>--<520.0,466.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* E (U+0045): L<<42.0,690.0>--<465.0,690.0>> -> L<<465.0,690.0>--<553.0,696.0>>

	* E (U+0045): L<<465.0,690.0>--<553.0,696.0>> -> L<<553.0,696.0>--<564.0,696.0>>

	* F (U+0046): L<<42.0,690.0>--<455.0,690.0>> -> L<<455.0,690.0>--<543.0,696.0>>

	* F (U+0046): L<<455.0,690.0>--<543.0,696.0>> -> L<<543.0,696.0>--<554.0,696.0>>

	* T (U+0054): L<<141.0,690.0>--<567.0,690.0>> -> L<<567.0,690.0>--<655.0,696.0>>

	* T (U+0054): L<<42.0,696.0>--<53.0,696.0>> -> L<<53.0,696.0>--<141.0,690.0>>

	* T (U+0054): L<<53.0,696.0>--<141.0,690.0>> -> L<<141.0,690.0>--<567.0,690.0>>

	* T (U+0054): L<<567.0,690.0>--<655.0,696.0>> -> L<<655.0,696.0>--<666.0,696.0>>

	* d (U+0064): L<<410.0,467.0>--<410.0,467.0>> -> L<<410.0,467.0>--<415.0,467.0>>

	* d (U+0064): L<<415.0,467.0>--<410.0,617.0>> -> L<<410.0,617.0>--<410.0,636.0>>

	* h (U+0068): L<<192.0,765.0>--<192.0,578.0>> -> L<<192.0,578.0>--<183.0,401.0>> 

	* p (U+0070): L<<188.0,13.0>--<192.0,-137.0>> -> L<<192.0,-137.0>--<192.0,-166.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[23] Platypi_August16-Italic.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/googlefonts/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00A0 (NO-BREAK SPACE)


	- 0x00B0 (DEGREE SIGN)


	- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


	- 0x0132 (LATIN CAPITAL LIGATURE IJ)


	- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


	- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


	- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


	- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


	- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


	- 0x0156 (LATIN CAPITAL LETTER R WITH CEDILLA)


	- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


	- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


	- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


	- 0x0133 (LATIN SMALL LIGATURE IJ)


	- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


	- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


	- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


	- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


	- 0x0157 (LATIN SMALL LETTER R WITH CEDILLA)


	- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


	- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


	- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


	- 0x00AA (FEMININE ORDINAL INDICATOR)


	- 0x00BA (MASCULINE ORDINAL INDICATOR)


	- 0x00A7 (SECTION SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A5 (YEN SIGN)


	- 0x007E (TILDE)


	- 0x005E (CIRCUMFLEX ACCENT)


	- 0x0312 (COMBINING TURNED COMMA ABOVE)
 

	- 0x0326 (COMBINING COMMA BELOW)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "Platypi_August16" contains the following characters which are not allowed: "_". [code: forbidden-characters]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Platypi-Regular.ttf', 'fonts/ttf/Platypi_August16-Italic.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 280, but got 265 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (735) and hhea ascent (935) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Font contains glyphs for whitespace characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphs">com.google.fonts/check/whitespace_glyphs</a>)</summary><div>


* 🔥 **FAIL** Whitespace glyph missing for codepoint 0x00A0. [code: missing-whitespace-glyph-0x00A0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ị̃ ị̆ ị̇ ị̊ ị̋ ị̌ ĩ̱ ĭ̱ i̱̇ i̱̊ i̱̋ ǐ̱ ĩ̵ ĭ̵ i̵̇ i̵̊ i̵̋ ǐ̵ ĩ̶ ĭ̶ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret positioning values for these ligature glyphs:
	- f_f
	- f_f_i
	- f_f_l

   [code: incomplete-caret-pos-data]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 2	Expected: 1

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 2	Expected: 1

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 469 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 410:
greater, less

Width = 404:
multiply

Width = 490:
divide

Width = 470:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=323.0,Y=638.0 (should be at cap-height 640?)

	* one (U+0031): X=322.0,Y=638.0 (should be at cap-height 640?)

	* C (U+0043): X=549.0,Y=642.0 (should be at cap-height 640?)

	* G (U+0047): X=556.0,Y=641.5 (should be at cap-height 640?)

	* Q (U+0051): X=382.0,Y=-1.0 (should be at baseline 0?)

	* S (U+0053): X=100.0,Y=0.5 (should be at baseline 0?)

	* g (U+0067): X=415.0,Y=429.5 (should be at x-height 430?)

	* s (U+0073): X=163.5,Y=428.0 (should be at x-height 430?)

	* x (U+0078): X=490.0,Y=431.0 (should be at x-height 430?)

	* x (U+0078): X=-43.0,Y=-1.0 (should be at baseline 0?)

	* z (U+007A): X=408.0,Y=432.0 (should be at x-height 430?)

	* Atilde (U+00C3): X=363.0,Y=735.5 (should be at ascender 735?)

	* Atilde (U+00C3): X=317.5,Y=737.0 (should be at ascender 735?)

	* Ccedilla (U+00C7): X=549.0,Y=642.0 (should be at cap-height 640?)

	* Ntilde (U+00D1): X=420.0,Y=735.5 (should be at ascender 735?)

	* Ntilde (U+00D1): X=374.5,Y=737.0 (should be at ascender 735?)

	* Otilde (U+00D5): X=440.0,Y=735.5 (should be at ascender 735?)

	* Otilde (U+00D5): X=394.5,Y=737.0 (should be at ascender 735?)

	* Cacute (U+0106): X=549.0,Y=642.0 (should be at cap-height 640?)

	* Ccircumflex (U+0108): X=549.0,Y=642.0 (should be at cap-height 640?)

	* Cdotaccent (U+010A): X=549.0,Y=642.0 (should be at cap-height 640?)

	* Ccaron (U+010C): X=549.0,Y=642.0 (should be at cap-height 640?)

	* Gcircumflex (U+011C): X=556.0,Y=641.5 (should be at cap-height 640?)

	* Gbreve (U+011E): X=556.0,Y=641.5 (should be at cap-height 640?)

	* Gdotaccent (U+0120): X=556.0,Y=641.5 (should be at cap-height 640?)

	* Sacute (U+015A): X=100.0,Y=0.5 (should be at baseline 0?)

	* Scircumflex (U+015C): X=100.0,Y=0.5 (should be at baseline 0?)

	* Scedilla (U+015E): X=100.0,Y=0.5 (should be at baseline 0?)

	* Scaron (U+0160): X=100.0,Y=0.5 (should be at baseline 0?)

	* Utilde (U+0168): X=399.0,Y=735.5 (should be at ascender 735?)

	* Utilde (U+0168): X=353.5,Y=737.0 (should be at ascender 735?)

	* Gcaron (U+01E6): X=556.0,Y=641.5 (should be at cap-height 640?)

	* uni1EBC (U+1EBC): X=359.0,Y=735.5 (should be at ascender 735?)

	* uni1EBC (U+1EBC): X=313.5,Y=737.0 (should be at ascender 735?)

	* uni1EF8 (U+1EF8): X=388.0,Y=735.5 (should be at ascender 735?)

	* uni1EF8 (U+1EF8): X=342.5,Y=737.0 (should be at ascender 735?)

	* quotedblleft (U+201C): X=219.0,Y=641.0 (should be at cap-height 640?)

	* quotedblleft (U+201C): X=219.0,Y=641.0 (should be at cap-height 640?)

	* quotedblleft (U+201C): X=393.0,Y=641.0 (should be at cap-height 640?) 

	* quotedblleft (U+201C): X=393.0,Y=641.0 (should be at cap-height 640?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<344.0,640.0>--<773.0,640.0>> -> L<<773.0,640.0>--<875.0,646.0>>

	* AE (U+00C6): L<<773.0,640.0>--<875.0,646.0>> -> L<<875.0,646.0>--<884.0,646.0>>

	* AEacute (U+01FC): L<<344.0,640.0>--<773.0,640.0>> -> L<<773.0,640.0>--<875.0,646.0>>

	* AEacute (U+01FC): L<<773.0,640.0>--<875.0,646.0>> -> L<<875.0,646.0>--<884.0,646.0>>

	* E (U+0045): L<<136.0,640.0>--<490.0,640.0>> -> L<<490.0,640.0>--<592.0,646.0>>

	* E (U+0045): L<<490.0,640.0>--<592.0,646.0>> -> L<<592.0,646.0>--<601.0,646.0>>

	* Eacute (U+00C9): L<<136.0,640.0>--<490.0,640.0>> -> L<<490.0,640.0>--<592.0,646.0>>

	* Eacute (U+00C9): L<<490.0,640.0>--<592.0,646.0>> -> L<<592.0,646.0>--<601.0,646.0>>

	* Ebreve (U+0114): L<<136.0,640.0>--<490.0,640.0>> -> L<<490.0,640.0>--<592.0,646.0>>

	* Ebreve (U+0114): L<<490.0,640.0>--<592.0,646.0>> -> L<<592.0,646.0>--<601.0,646.0>>

	* Ecaron (U+011A): L<<136.0,640.0>--<490.0,640.0>> -> L<<490.0,640.0>--<592.0,646.0>>

	* Ecaron (U+011A): L<<490.0,640.0>--<592.0,646.0>> -> L<<592.0,646.0>--<601.0,646.0>>

	* Ecircumflex (U+00CA): L<<136.0,640.0>--<490.0,640.0>> -> L<<490.0,640.0>--<592.0,646.0>>

	* Ecircumflex (U+00CA): L<<490.0,640.0>--<592.0,646.0>> -> L<<592.0,646.0>--<601.0,646.0>>

	* Edieresis (U+00CB): L<<136.0,640.0>--<490.0,640.0>> -> L<<490.0,640.0>--<592.0,646.0>>

	* Edieresis (U+00CB): L<<490.0,640.0>--<592.0,646.0>> -> L<<592.0,646.0>--<601.0,646.0>>

	* Edotaccent (U+0116): L<<136.0,640.0>--<490.0,640.0>> -> L<<490.0,640.0>--<592.0,646.0>>

	* Edotaccent (U+0116): L<<490.0,640.0>--<592.0,646.0>> -> L<<592.0,646.0>--<601.0,646.0>>

	* Egrave (U+00C8): L<<136.0,640.0>--<490.0,640.0>> -> L<<490.0,640.0>--<592.0,646.0>>

	* Egrave (U+00C8): L<<490.0,640.0>--<592.0,646.0>> -> L<<592.0,646.0>--<601.0,646.0>>

	* Emacron (U+0112): L<<136.0,640.0>--<490.0,640.0>> -> L<<490.0,640.0>--<592.0,646.0>>

	* Emacron (U+0112): L<<490.0,640.0>--<592.0,646.0>> -> L<<592.0,646.0>--<601.0,646.0>>

	* Eogonek (U+0118): L<<136.0,640.0>--<490.0,640.0>> -> L<<490.0,640.0>--<592.0,646.0>>

	* Eogonek (U+0118): L<<490.0,640.0>--<592.0,646.0>> -> L<<592.0,646.0>--<601.0,646.0>>

	* F (U+0046): L<<136.0,640.0>--<474.0,640.0>> -> L<<474.0,640.0>--<573.0,646.0>>

	* F (U+0046): L<<474.0,640.0>--<573.0,646.0>> -> L<<573.0,646.0>--<583.0,646.0>>

	* OE (U+0152): L<<469.0,640.0>--<839.0,640.0>> -> L<<839.0,640.0>--<941.0,646.0>>

	* OE (U+0152): L<<839.0,640.0>--<941.0,646.0>> -> L<<941.0,646.0>--<950.0,646.0>>

	* T (U+0054): L<<102.0,646.0>--<112.0,646.0>> -> L<<112.0,646.0>--<211.0,640.0>>

	* T (U+0054): L<<112.0,646.0>--<211.0,640.0>> -> L<<211.0,640.0>--<565.0,640.0>>

	* T (U+0054): L<<211.0,640.0>--<565.0,640.0>> -> L<<565.0,640.0>--<667.0,646.0>>

	* T (U+0054): L<<565.0,640.0>--<667.0,646.0>> -> L<<667.0,646.0>--<677.0,646.0>>

	* Tcaron (U+0164): L<<102.0,646.0>--<112.0,646.0>> -> L<<112.0,646.0>--<211.0,640.0>>

	* Tcaron (U+0164): L<<112.0,646.0>--<211.0,640.0>> -> L<<211.0,640.0>--<565.0,640.0>>

	* Tcaron (U+0164): L<<211.0,640.0>--<565.0,640.0>> -> L<<565.0,640.0>--<667.0,646.0>>

	* Tcaron (U+0164): L<<565.0,640.0>--<667.0,646.0>> -> L<<667.0,646.0>--<677.0,646.0>>

	* Tmacronbelow (U+1E6E): L<<102.0,646.0>--<112.0,646.0>> -> L<<112.0,646.0>--<211.0,640.0>>

	* Tmacronbelow (U+1E6E): L<<112.0,646.0>--<211.0,640.0>> -> L<<211.0,640.0>--<565.0,640.0>>

	* Tmacronbelow (U+1E6E): L<<211.0,640.0>--<565.0,640.0>> -> L<<565.0,640.0>--<667.0,646.0>>

	* Tmacronbelow (U+1E6E): L<<565.0,640.0>--<667.0,646.0>> -> L<<667.0,646.0>--<677.0,646.0>>

	* U (U+0055): L<<482.0,244.0>--<491.0,280.0>> -> L<<491.0,280.0>--<554.0,575.0>>

	* Uacute (U+00DA): L<<482.0,244.0>--<491.0,280.0>> -> L<<491.0,280.0>--<554.0,575.0>>

	* Ubreve (U+016C): L<<482.0,244.0>--<491.0,280.0>> -> L<<491.0,280.0>--<554.0,575.0>>

	* Ucircumflex (U+00DB): L<<482.0,244.0>--<491.0,280.0>> -> L<<491.0,280.0>--<554.0,575.0>>

	* Udieresis (U+00DC): L<<482.0,244.0>--<491.0,280.0>> -> L<<491.0,280.0>--<554.0,575.0>>

	* Ugrave (U+00D9): L<<482.0,244.0>--<491.0,280.0>> -> L<<491.0,280.0>--<554.0,575.0>>

	* Uhungarumlaut (U+0170): L<<482.0,244.0>--<491.0,280.0>> -> L<<491.0,280.0>--<554.0,575.0>>

	* Umacron (U+016A): L<<482.0,244.0>--<491.0,280.0>> -> L<<491.0,280.0>--<554.0,575.0>>

	* Uogonek (U+0172): L<<482.0,244.0>--<491.0,280.0>> -> L<<491.0,280.0>--<554.0,575.0>>

	* Uring (U+016E): L<<482.0,244.0>--<491.0,280.0>> -> L<<491.0,280.0>--<554.0,575.0>>

	* Utilde (U+0168): L<<482.0,244.0>--<491.0,280.0>> -> L<<491.0,280.0>--<554.0,575.0>>

	* Z (U+005A): L<<120.0,646.0>--<130.0,646.0>> -> L<<130.0,646.0>--<229.0,640.0>>

	* Z (U+005A): L<<130.0,646.0>--<229.0,640.0>> -> L<<229.0,640.0>--<552.0,640.0>>

	* Zacute (U+0179): L<<120.0,646.0>--<130.0,646.0>> -> L<<130.0,646.0>--<229.0,640.0>>

	* Zacute (U+0179): L<<130.0,646.0>--<229.0,640.0>> -> L<<229.0,640.0>--<552.0,640.0>>

	* Zcaron (U+017D): L<<120.0,646.0>--<130.0,646.0>> -> L<<130.0,646.0>--<229.0,640.0>>

	* Zcaron (U+017D): L<<130.0,646.0>--<229.0,640.0>> -> L<<229.0,640.0>--<552.0,640.0>>

	* Zdotaccent (U+017B): L<<120.0,646.0>--<130.0,646.0>> -> L<<130.0,646.0>--<229.0,640.0>>

	* Zdotaccent (U+017B): L<<130.0,646.0>--<229.0,640.0>> -> L<<229.0,640.0>--<552.0,640.0>>

	* b (U+0062): L<<284.0,735.0>--<213.0,430.0>> -> L<<213.0,430.0>--<157.0,227.0>>

	* h (U+0068): L<<284.0,735.0>--<213.0,430.0>> -> L<<213.0,430.0>--<151.0,227.0>>

	* hbar (U+0127): L<<284.0,735.0>--<213.0,430.0>> -> L<<213.0,430.0>--<151.0,227.0>>

	* hcircumflex (U+0125): L<<284.0,735.0>--<213.0,430.0>> -> L<<213.0,430.0>--<151.0,227.0>>

	* k (U+006B): L<<284.0,735.0>--<223.0,474.0>> -> L<<223.0,474.0>--<183.0,330.0>>

	* q (U+0071): L<<226.0,-218.0>--<276.0,0.0>> -> L<<276.0,0.0>--<334.0,203.0>>

	* thorn (U+00FE): L<<284.0,735.0>--<198.0,368.0>> -> L<<198.0,368.0>--<158.0,227.0>>

	* trademark (U+2122): L<<101.0,643.0>--<107.0,643.0>> -> L<<107.0,643.0>--<149.0,640.0>>

	* trademark (U+2122): L<<107.0,643.0>--<149.0,640.0>> -> L<<149.0,640.0>--<252.0,640.0>>

	* trademark (U+2122): L<<149.0,640.0>--<252.0,640.0>> -> L<<252.0,640.0>--<296.0,643.0>>

	* trademark (U+2122): L<<252.0,640.0>--<296.0,643.0>> -> L<<296.0,643.0>--<303.0,643.0>>

	* uni0162 (U+0162): L<<102.0,646.0>--<112.0,646.0>> -> L<<112.0,646.0>--<211.0,640.0>>

	* uni0162 (U+0162): L<<112.0,646.0>--<211.0,640.0>> -> L<<211.0,640.0>--<565.0,640.0>>

	* uni0162 (U+0162): L<<211.0,640.0>--<565.0,640.0>> -> L<<565.0,640.0>--<667.0,646.0>>

	* uni0162 (U+0162): L<<565.0,640.0>--<667.0,646.0>> -> L<<667.0,646.0>--<677.0,646.0>>

	* uni1EB8 (U+1EB8): L<<136.0,640.0>--<490.0,640.0>> -> L<<490.0,640.0>--<592.0,646.0>>

	* uni1EB8 (U+1EB8): L<<490.0,640.0>--<592.0,646.0>> -> L<<592.0,646.0>--<601.0,646.0>>

	* uni1EBC (U+1EBC): L<<136.0,640.0>--<490.0,640.0>> -> L<<490.0,640.0>--<592.0,646.0>>

	* uni1EBC (U+1EBC): L<<490.0,640.0>--<592.0,646.0>> -> L<<592.0,646.0>--<601.0,646.0>> 

	* uni1EE4 (U+1EE4): L<<482.0,244.0>--<491.0,280.0>> -> L<<491.0,280.0>--<554.0,575.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* f (U+0066): B<<418.0,674.0>-<415.0,676.0>-<414.0,677.0>>/L<<414.0,677.0>--<418.0,674.0>> = 8.13010235415596

	* f (U+0066): L<<414.0,677.0>--<418.0,674.0>>/B<<418.0,674.0>-<415.0,676.0>-<414.0,677.0>> = 3.1798301198640497

	* z (U+007A): L<<444.0,418.0>--<117.0,55.0>>/B<<117.0,55.0>-<163.0,90.0>-<225.0,90.0>> = 10.720235089498024

	* zacute (U+017A): L<<444.0,418.0>--<117.0,55.0>>/B<<117.0,55.0>-<163.0,90.0>-<225.0,90.0>> = 10.720235089498024 

	* zcaron (U+017E): L<<444.0,418.0>--<117.0,55.0>>/B<<117.0,55.0>-<163.0,90.0>-<225.0,90.0>> = 10.720235089498024 [code: found-jaggy-segments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 2 | 22 | 22 | 245 | 14 | 170 | 0 |
| 0% | 5% | 5% | 52% | 3% | 36% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
