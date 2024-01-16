## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[2] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Each font in a family must have the same set of vertical metrics values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/vertical_metrics">com.google.fonts/check/family/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** sTypoAscender is not the same across the family:
Platypi Semi Bold Italic: 765
Platypi Light: 935
Platypi: 935
Platypi Extra Bold Italic: 765
Platypi Bold: 935
Platypi Light Italic: 765
Platypi Extra Bold: 935
Platypi Regular Italic: 765
Platypi Bold Italic: 765
Platypi Semi Bold: 935 [code: sTypoAscender-mismatch]
* 🔥 **FAIL** sTypoDescender is not the same across the family:
Platypi Semi Bold Italic: -235
Platypi Light: 251
Platypi: 251
Platypi Extra Bold Italic: -235
Platypi Bold: 251
Platypi Light Italic: -235
Platypi Extra Bold: 251
Platypi Regular Italic: -235
Platypi Bold Italic: -235
Platypi Semi Bold: 251 [code: sTypoDescender-mismatch]
* 🔥 **FAIL** sTypoLineGap is not the same across the family:
Platypi Semi Bold Italic: 200
Platypi Light: 0
Platypi: 0
Platypi Extra Bold Italic: 200
Platypi Bold: 0
Platypi Light Italic: 200
Platypi Extra Bold: 0
Platypi Regular Italic: 200
Platypi Bold Italic: 200
Platypi Semi Bold: 0 [code: sTypoLineGap-mismatch]
* 🔥 **FAIL** usWinAscent is not the same across the family:
Platypi Semi Bold Italic: 965
Platypi Light: 1123
Platypi: 1123
Platypi Extra Bold Italic: 965
Platypi Bold: 1123
Platypi Light Italic: 965
Platypi Extra Bold: 1123
Platypi Regular Italic: 965
Platypi Bold Italic: 965
Platypi Semi Bold: 1123 [code: usWinAscent-mismatch]
* 🔥 **FAIL** usWinDescent is not the same across the family:
Platypi Semi Bold Italic: 235
Platypi Light: 342
Platypi: 342
Platypi Extra Bold Italic: 235
Platypi Bold: 342
Platypi Light Italic: 235
Platypi Extra Bold: 342
Platypi Regular Italic: 235
Platypi Bold Italic: 235
Platypi Semi Bold: 342 [code: usWinDescent-mismatch]
* 🔥 **FAIL** ascent is not the same across the family:
Platypi Semi Bold Italic: 965
Platypi Light: 935
Platypi: 935
Platypi Extra Bold Italic: 965
Platypi Bold: 935
Platypi Light Italic: 965
Platypi Extra Bold: 935
Platypi Regular Italic: 965
Platypi Bold Italic: 965
Platypi Semi Bold: 935 [code: ascent-mismatch]
* 🔥 **FAIL** descent is not the same across the family:
Platypi Semi Bold Italic: -235
Platypi Light: 251
Platypi: 251
Platypi Extra Bold Italic: -235
Platypi Bold: 251
Platypi Light Italic: -235
Platypi Extra Bold: 251
Platypi Regular Italic: -235
Platypi Bold Italic: -235
Platypi Semi Bold: 251 [code: descent-mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Make sure all font files have the same version value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/family/equal_font_versions">com.google.fonts/check/family/equal_font_versions</a>)</summary><div>


* ⚠ **WARN** Version info differs among font files of the same font project.
These were the version values found:
* fonts/ttf/Platypi-SemiBoldItalic.ttf: 0.350006103515625
* fonts/ttf/Platypi-Light.ttf: 0.399993896484375
* fonts/ttf/Platypi-Regular.ttf: 0.399993896484375
* fonts/ttf/Platypi-ExtraBoldItalic.ttf: 0.350006103515625
* fonts/ttf/Platypi-Bold.ttf: 0.399993896484375
* fonts/ttf/Platypi-LightItalic.ttf: 0.350006103515625
* fonts/ttf/Platypi-ExtraBold.ttf: 0.399993896484375
* fonts/ttf/Platypi-RegularItalic.ttf: 0.350006103515625
* fonts/ttf/Platypi-BoldItalic.ttf: 0.350006103515625
* fonts/ttf/Platypi-SemiBold.ttf: 0.399993896484375
 [code: mismatch]
</div></details><br></div></details><details><summary><b>[24] Platypi-SemiBoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'Semi Bold Italic'. Expected OS/2 usWeightClass is 700, got 600. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Version format is correct in 'name' table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/version_format">com.google.fonts/check/name/version_format</a>)</summary><div>


* 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000. Current version string is: "Version 0.350; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.33]" [code: bad-version-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Platypi Semi Bold Italic | Platypi Semi |
| Subfamily Name | Regular | Bold Italic |
| Full Name | Platypi Semi Bold Italic | Platypi Semi Bold Italic |
| Poscript Name | Platypi-SemiBoldItalic | PlatypiSemi-BoldItalic |
| Typographic Family Name | Platypi | N/A |
| Typographic Subfamily Name | Semi Bold Italic | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Platypi-SemiBoldItalic.ttf', 'fonts/ttf/Platypi-ExtraBoldItalic.ttf', 'fonts/ttf/Platypi-LightItalic.ttf', 'fonts/ttf/Platypi-RegularItalic.ttf', 'fonts/ttf/Platypi-BoldItalic.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1123, but got 965 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 342, but got 235 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (765) and hhea ascent (965) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle ITALIC bit should be set. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be unset. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection ITALIC bit should be set. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table IDs 1, 2, 16, 17 to conform to Italic style. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/name/italic_names">com.google.fonts/check/name/italic_names</a>)</summary><div>


* 🔥 **FAIL** Name ID 1 (Family Name) must not contain 'Italic'. [code: bad-familyname]
* 🔥 **FAIL** Name ID 2 (Subfamily Name) does not conform to specs. Only R/I/B/BI are allowed.
Got: 'Regular'. [code: bad-subfamilyname]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'BOLT' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Platypi Semi Bold Italic' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.TRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

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

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<282.0,690.0>--<723.0,690.0>> -> L<<723.0,690.0>--<856.0,698.0>>

	* AE (U+00C6): L<<723.0,690.0>--<856.0,698.0>> -> L<<856.0,698.0>--<871.0,698.0>>

	* AEacute (U+01FC): L<<282.0,690.0>--<723.0,690.0>> -> L<<723.0,690.0>--<856.0,698.0>>

	* AEacute (U+01FC): L<<723.0,690.0>--<856.0,698.0>> -> L<<856.0,698.0>--<871.0,698.0>>

	* B (U+0042): L<<276.0,393.0>--<283.0,393.0>> -> L<<283.0,393.0>--<393.0,397.0>>

	* E (U+0045): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* E (U+0045): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* Eacute (U+00C9): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* Eacute (U+00C9): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* Ebreve (U+0114): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* Ebreve (U+0114): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* Ecaron (U+011A): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* Ecaron (U+011A): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* Ecircumflex (U+00CA): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* Ecircumflex (U+00CA): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* Edieresis (U+00CB): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* Edieresis (U+00CB): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* Edotaccent (U+0116): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* Edotaccent (U+0116): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* Egrave (U+00C8): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* Egrave (U+00C8): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* Emacron (U+0112): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* Emacron (U+0112): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* Eogonek (U+0118): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* Eogonek (U+0118): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* F (U+0046): L<<123.0,690.0>--<480.0,690.0>> -> L<<480.0,690.0>--<613.0,698.0>>

	* F (U+0046): L<<480.0,690.0>--<613.0,698.0>> -> L<<613.0,698.0>--<628.0,698.0>>

	* K (U+004B): L<<801.0,671.0>--<673.0,596.0>> -> L<<673.0,596.0>--<449.0,439.0>>

	* OE (U+0152): L<<516.0,690.0>--<867.0,690.0>> -> L<<867.0,690.0>--<1000.0,698.0>>

	* OE (U+0152): L<<867.0,690.0>--<1000.0,698.0>> -> L<<1000.0,698.0>--<1015.0,698.0>>

	* T (U+0054): L<<135.0,698.0>--<150.0,698.0>> -> L<<150.0,698.0>--<278.0,690.0>>

	* T (U+0054): L<<150.0,698.0>--<278.0,690.0>> -> L<<278.0,690.0>--<586.0,690.0>>

	* T (U+0054): L<<278.0,690.0>--<586.0,690.0>> -> L<<586.0,690.0>--<732.0,698.0>>

	* T (U+0054): L<<586.0,690.0>--<732.0,698.0>> -> L<<732.0,698.0>--<748.0,698.0>>

	* Tcaron (U+0164): L<<135.0,698.0>--<150.0,698.0>> -> L<<150.0,698.0>--<278.0,690.0>>

	* Tcaron (U+0164): L<<150.0,698.0>--<278.0,690.0>> -> L<<278.0,690.0>--<586.0,690.0>>

	* Tcaron (U+0164): L<<278.0,690.0>--<586.0,690.0>> -> L<<586.0,690.0>--<732.0,698.0>>

	* Tcaron (U+0164): L<<586.0,690.0>--<732.0,698.0>> -> L<<732.0,698.0>--<748.0,698.0>>

	* Tmacronbelow (U+1E6E): L<<135.0,698.0>--<150.0,698.0>> -> L<<150.0,698.0>--<278.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<150.0,698.0>--<278.0,690.0>> -> L<<278.0,690.0>--<586.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<278.0,690.0>--<586.0,690.0>> -> L<<586.0,690.0>--<732.0,698.0>>

	* Tmacronbelow (U+1E6E): L<<586.0,690.0>--<732.0,698.0>> -> L<<732.0,698.0>--<748.0,698.0>>

	* Z (U+005A): L<<136.0,702.0>--<151.0,702.0>> -> L<<151.0,702.0>--<291.0,690.0>>

	* Z (U+005A): L<<151.0,702.0>--<291.0,690.0>> -> L<<291.0,690.0>--<654.0,690.0>>

	* Zacute (U+0179): L<<136.0,702.0>--<151.0,702.0>> -> L<<151.0,702.0>--<291.0,690.0>>

	* Zacute (U+0179): L<<151.0,702.0>--<291.0,690.0>> -> L<<291.0,690.0>--<654.0,690.0>>

	* Zcaron (U+017D): L<<136.0,702.0>--<151.0,702.0>> -> L<<151.0,702.0>--<291.0,690.0>>

	* Zcaron (U+017D): L<<151.0,702.0>--<291.0,690.0>> -> L<<291.0,690.0>--<654.0,690.0>>

	* Zdotaccent (U+017B): L<<136.0,702.0>--<151.0,702.0>> -> L<<151.0,702.0>--<291.0,690.0>>

	* Zdotaccent (U+017B): L<<151.0,702.0>--<291.0,690.0>> -> L<<291.0,690.0>--<654.0,690.0>>

	* three (U+0033): L<<301.0,331.0>--<308.0,363.0>> -> L<<308.0,363.0>--<316.0,393.0>>

	* trademark (U+2122): L<<209.0,690.0>--<341.0,690.0>> -> L<<341.0,690.0>--<402.0,696.0>>

	* trademark (U+2122): L<<341.0,690.0>--<402.0,696.0>> -> L<<402.0,696.0>--<411.0,696.0>>

	* uni00B5 (U+00B5): L<<-42.0,-236.0>--<74.0,169.0>> -> L<<74.0,169.0>--<75.0,173.0>>

	* uni00B5 (U+00B5): L<<74.0,169.0>--<75.0,173.0>> -> L<<75.0,173.0>--<129.0,362.0>>

	* uni0136 (U+0136): L<<801.0,671.0>--<673.0,596.0>> -> L<<673.0,596.0>--<449.0,439.0>>

	* uni021A (U+021A): L<<135.0,698.0>--<150.0,698.0>> -> L<<150.0,698.0>--<278.0,690.0>>

	* uni021A (U+021A): L<<150.0,698.0>--<278.0,690.0>> -> L<<278.0,690.0>--<586.0,690.0>>

	* uni021A (U+021A): L<<278.0,690.0>--<586.0,690.0>> -> L<<586.0,690.0>--<732.0,698.0>>

	* uni021A (U+021A): L<<586.0,690.0>--<732.0,698.0>> -> L<<732.0,698.0>--<748.0,698.0>>

	* uni1EB8 (U+1EB8): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* uni1EB8 (U+1EB8): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* uni1EBA (U+1EBA): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* uni1EBA (U+1EBA): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* uni1EBC (U+1EBC): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* uni1EBC (U+1EBC): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* uni1EBE (U+1EBE): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* uni1EBE (U+1EBE): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* uni1EC0 (U+1EC0): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* uni1EC0 (U+1EC0): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* uni1EC2 (U+1EC2): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* uni1EC2 (U+1EC2): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* uni1EC4 (U+1EC4): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>>

	* uni1EC4 (U+1EC4): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>>

	* uni1EC6 (U+1EC6): L<<123.0,690.0>--<492.0,690.0>> -> L<<492.0,690.0>--<625.0,698.0>> 

	* uni1EC6 (U+1EC6): L<<492.0,690.0>--<625.0,698.0>> -> L<<625.0,698.0>--<640.0,698.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[16] Platypi-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Version format is correct in 'name' table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/version_format">com.google.fonts/check/name/version_format</a>)</summary><div>


* 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000. Current version string is: "Version %d.%03d; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.33]" [code: bad-version-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1186 when it should be at least 1200 [code: bad-hhea-range]
* 🔥 **FAIL** The OS/2 sTypoDescender must be negative or zero. This font has a strictly positive value. [code: typo-descender]
* 🔥 **FAIL** The hhea descender must be negative or zero. This font has a strictly positive value. [code: hhea-descent]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Platypi-SemiBoldItalic.ttf', 'fonts/ttf/Platypi-ExtraBoldItalic.ttf', 'fonts/ttf/Platypi-LightItalic.ttf', 'fonts/ttf/Platypi-RegularItalic.ttf', 'fonts/ttf/Platypi-BoldItalic.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ j̦̓ į̆ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** name version string for platform 3, encoding 1 ("Version %d.%03d; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.33]"), could not be parsed. [code: parse]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'BOLT' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=240.5,Y=688.0 (should be at cap-height 690?)

	* ampersand (U+0026): X=434.5,Y=690.5 (should be at cap-height 690?)

	* ampersand (U+0026): X=747.0,Y=-0.5 (should be at baseline 0?)

	* asterisk (U+002A): X=30.0,Y=692.0 (should be at cap-height 690?)

	* asterisk (U+002A): X=350.0,Y=692.0 (should be at cap-height 690?)

	* three (U+0033): X=159.0,Y=2.0 (should be at baseline 0?)

	* three (U+0033): X=171.5,Y=690.5 (should be at cap-height 690?)

	* five (U+0035): X=160.5,Y=2.0 (should be at baseline 0?)

	* F (U+0046): X=469.0,Y=249.0 (should be at descender 251?)

	* F (U+0046): X=453.0,Y=249.0 (should be at descender 251?)

	* G (U+0047): X=561.0,Y=252.0 (should be at descender 251?)

	* bracketleft (U+005B): X=119.0,Y=692.0 (should be at cap-height 690?)

	* bracketright (U+005D): X=152.0,Y=692.0 (should be at cap-height 690?)

	* a (U+0061): X=153.5,Y=479.0 (should be at x-height 480?)

	* c (U+0063): X=138.0,Y=250.0 (should be at descender 251?)

	* e (U+0065): X=138.0,Y=250.0 (should be at descender 251?)

	* q (U+0071): X=386.5,Y=482.0 (should be at x-height 480?)

	* r (U+0072): X=426.0,Y=482.0 (should be at x-height 480?)

	* s (U+0073): X=361.5,Y=479.0 (should be at x-height 480?)

	* braceleft (U+007B): X=110.0,Y=2.0 (should be at baseline 0?)

	* braceleft (U+007B): X=183.5,Y=2.0 (should be at baseline 0?)

	* braceright (U+007D): X=127.0,Y=2.0 (should be at baseline 0?)

	* braceright (U+007D): X=200.0,Y=2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=158.0,Y=251.5 (should be at descender 251?)

	* Thorn (U+00DE): X=521.5,Y=250.0 (should be at descender 251?)

	* germandbls (U+00DF): X=499.5,Y=688.5 (should be at cap-height 690?)

	* germandbls (U+00DF): X=299.5,Y=-1.5 (should be at baseline 0?)

	* germandbls (U+00DF): X=403.5,Y=690.5 (should be at cap-height 690?)

	* ccedilla (U+00E7): X=138.0,Y=250.0 (should be at descender 251?)

	* egrave (U+00E8): X=138.0,Y=250.0 (should be at descender 251?)

	* eacute (U+00E9): X=138.0,Y=250.0 (should be at descender 251?)

	* ecircumflex (U+00EA): X=138.0,Y=250.0 (should be at descender 251?)

	* edieresis (U+00EB): X=138.0,Y=250.0 (should be at descender 251?)

	* Aogonek (U+0104): X=555.0,Y=-2.0 (should be at baseline 0?)

	* cacute (U+0107): X=138.0,Y=250.0 (should be at descender 251?)

	* ccircumflex (U+0109): X=138.0,Y=250.0 (should be at descender 251?)

	* cdotaccent (U+010B): X=138.0,Y=250.0 (should be at descender 251?)

	* ccaron (U+010D): X=138.0,Y=250.0 (should be at descender 251?)

	* emacron (U+0113): X=138.0,Y=250.0 (should be at descender 251?)

	* ebreve (U+0115): X=138.0,Y=250.0 (should be at descender 251?)

	* edotaccent (U+0117): X=138.0,Y=250.0 (should be at descender 251?)

	* Eogonek (U+0118): X=406.0,Y=-2.0 (should be at baseline 0?)

	* eogonek (U+0119): X=138.0,Y=250.0 (should be at descender 251?)

	* ecaron (U+011B): X=138.0,Y=250.0 (should be at descender 251?)

	* Gcircumflex (U+011C): X=561.0,Y=252.0 (should be at descender 251?)

	* Gbreve (U+011E): X=561.0,Y=252.0 (should be at descender 251?)

	* Gdotaccent (U+0120): X=561.0,Y=252.0 (should be at descender 251?)

	* uni0122 (U+0122): X=561.0,Y=252.0 (should be at descender 251?)

	* Iogonek (U+012E): X=130.0,Y=-2.0 (should be at baseline 0?)

	* iogonek (U+012F): X=127.0,Y=-2.0 (should be at baseline 0?)

	* oe (U+0153): X=548.0,Y=250.0 (should be at descender 251?)

	* Gcaron (U+01E6): X=561.0,Y=252.0 (should be at descender 251?)

	* uni1E20 (U+1E20): X=561.0,Y=252.0 (should be at descender 251?)

	* uni1EAA (U+1EAA): X=489.5,Y=936.0 (should be at ascender 935?)

	* uni1EB3 (U+1EB3): X=232.0,Y=692.0 (should be at cap-height 690?)

	* uni1EB9 (U+1EB9): X=138.0,Y=250.0 (should be at descender 251?)

	* uni1EBB (U+1EBB): X=138.0,Y=250.0 (should be at descender 251?)

	* uni1EBD (U+1EBD): X=138.0,Y=250.0 (should be at descender 251?)

	* uni1EBF (U+1EBF): X=138.0,Y=250.0 (should be at descender 251?)

	* uni1EC1 (U+1EC1): X=138.0,Y=250.0 (should be at descender 251?)

	* uni1EC3 (U+1EC3): X=138.0,Y=250.0 (should be at descender 251?)

	* uni1EC4 (U+1EC4): X=455.5,Y=936.0 (should be at ascender 935?)

	* uni1EC5 (U+1EC5): X=138.0,Y=250.0 (should be at descender 251?)

	* uni1EC7 (U+1EC7): X=138.0,Y=250.0 (should be at descender 251?)

	* uni1ED6 (U+1ED6): X=532.5,Y=936.0 (should be at ascender 935?) 

	* infinity (U+221E): X=530.0,Y=250.0 (should be at descender 251?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<279.0,690.0>--<721.0,690.0>> -> L<<721.0,690.0>--<834.0,698.0>>

	* AE (U+00C6): L<<721.0,690.0>--<834.0,698.0>> -> L<<834.0,698.0>--<845.0,698.0>>

	* AEacute (U+01FC): L<<279.0,690.0>--<721.0,690.0>> -> L<<721.0,690.0>--<834.0,698.0>>

	* AEacute (U+01FC): L<<721.0,690.0>--<834.0,698.0>> -> L<<834.0,698.0>--<845.0,698.0>>

	* E (U+0045): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* E (U+0045): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* Eacute (U+00C9): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* Eacute (U+00C9): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* Ebreve (U+0114): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* Ebreve (U+0114): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* Ecaron (U+011A): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* Ecaron (U+011A): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* Ecircumflex (U+00CA): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* Ecircumflex (U+00CA): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* Edieresis (U+00CB): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* Edieresis (U+00CB): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* Edotaccent (U+0116): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* Edotaccent (U+0116): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* Egrave (U+00C8): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* Egrave (U+00C8): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* Emacron (U+0112): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* Emacron (U+0112): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* Eogonek (U+0118): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* Eogonek (U+0118): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* F (U+0046): L<<30.0,690.0>--<417.0,690.0>> -> L<<417.0,690.0>--<530.0,698.0>>

	* F (U+0046): L<<417.0,690.0>--<530.0,698.0>> -> L<<530.0,698.0>--<541.0,698.0>>

	* OE (U+0152): L<<413.0,690.0>--<799.0,690.0>> -> L<<799.0,690.0>--<912.0,698.0>>

	* OE (U+0152): L<<799.0,690.0>--<912.0,698.0>> -> L<<912.0,698.0>--<923.0,698.0>>

	* T (U+0054): L<<179.0,690.0>--<507.0,690.0>> -> L<<507.0,690.0>--<627.0,698.0>>

	* T (U+0054): L<<48.0,698.0>--<59.0,698.0>> -> L<<59.0,698.0>--<179.0,690.0>>

	* T (U+0054): L<<507.0,690.0>--<627.0,698.0>> -> L<<627.0,698.0>--<638.0,698.0>>

	* T (U+0054): L<<59.0,698.0>--<179.0,690.0>> -> L<<179.0,690.0>--<507.0,690.0>>

	* Tbar (U+0166): L<<179.0,690.0>--<507.0,690.0>> -> L<<507.0,690.0>--<627.0,698.0>>

	* Tbar (U+0166): L<<48.0,698.0>--<59.0,698.0>> -> L<<59.0,698.0>--<179.0,690.0>>

	* Tbar (U+0166): L<<507.0,690.0>--<627.0,698.0>> -> L<<627.0,698.0>--<638.0,698.0>>

	* Tbar (U+0166): L<<59.0,698.0>--<179.0,690.0>> -> L<<179.0,690.0>--<507.0,690.0>>

	* Tcaron (U+0164): L<<179.0,690.0>--<507.0,690.0>> -> L<<507.0,690.0>--<627.0,698.0>>

	* Tcaron (U+0164): L<<48.0,698.0>--<59.0,698.0>> -> L<<59.0,698.0>--<179.0,690.0>>

	* Tcaron (U+0164): L<<507.0,690.0>--<627.0,698.0>> -> L<<627.0,698.0>--<638.0,698.0>>

	* Tcaron (U+0164): L<<59.0,698.0>--<179.0,690.0>> -> L<<179.0,690.0>--<507.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<179.0,690.0>--<507.0,690.0>> -> L<<507.0,690.0>--<627.0,698.0>>

	* Tmacronbelow (U+1E6E): L<<48.0,698.0>--<59.0,698.0>> -> L<<59.0,698.0>--<179.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<507.0,690.0>--<627.0,698.0>> -> L<<627.0,698.0>--<638.0,698.0>>

	* Tmacronbelow (U+1E6E): L<<59.0,698.0>--<179.0,690.0>> -> L<<179.0,690.0>--<507.0,690.0>>

	* Z (U+005A): L<<56.0,698.0>--<72.0,698.0>> -> L<<72.0,698.0>--<212.0,690.0>>

	* Z (U+005A): L<<72.0,698.0>--<212.0,690.0>> -> L<<212.0,690.0>--<572.0,690.0>>

	* Zacute (U+0179): L<<56.0,698.0>--<72.0,698.0>> -> L<<72.0,698.0>--<212.0,690.0>>

	* Zacute (U+0179): L<<72.0,698.0>--<212.0,690.0>> -> L<<212.0,690.0>--<572.0,690.0>>

	* Zcaron (U+017D): L<<56.0,698.0>--<72.0,698.0>> -> L<<72.0,698.0>--<212.0,690.0>>

	* Zcaron (U+017D): L<<72.0,698.0>--<212.0,690.0>> -> L<<212.0,690.0>--<572.0,690.0>>

	* Zdotaccent (U+017B): L<<56.0,698.0>--<72.0,698.0>> -> L<<72.0,698.0>--<212.0,690.0>>

	* Zdotaccent (U+017B): L<<72.0,698.0>--<212.0,690.0>> -> L<<212.0,690.0>--<572.0,690.0>>

	* f (U+0066): L<<207.0,477.0>--<362.0,492.0>> -> L<<362.0,492.0>--<374.0,492.0>>

	* fi (U+FB01): L<<207.0,469.0>--<539.0,487.0>> -> L<<539.0,487.0>--<562.0,487.0>>

	* t (U+0074): L<<187.0,476.0>--<384.0,492.0>> -> L<<384.0,492.0>--<396.0,492.0>>

	* tbar (U+0167): L<<187.0,476.0>--<384.0,492.0>> -> L<<384.0,492.0>--<396.0,492.0>>

	* tcaron (U+0165): L<<187.0,476.0>--<384.0,492.0>> -> L<<384.0,492.0>--<396.0,492.0>>

	* tmacronbelow (U+1E6F): L<<187.0,476.0>--<384.0,492.0>> -> L<<384.0,492.0>--<396.0,492.0>>

	* trademark (U+2122): L<<10.0,695.0>--<69.0,690.0>> -> L<<69.0,690.0>--<199.0,690.0>>

	* trademark (U+2122): L<<199.0,690.0>--<257.0,695.0>> -> L<<257.0,695.0>--<266.0,695.0>>

	* trademark (U+2122): L<<2.0,695.0>--<10.0,695.0>> -> L<<10.0,695.0>--<69.0,690.0>>

	* trademark (U+2122): L<<69.0,690.0>--<199.0,690.0>> -> L<<199.0,690.0>--<257.0,695.0>>

	* uni0162 (U+0162): L<<179.0,690.0>--<507.0,690.0>> -> L<<507.0,690.0>--<627.0,698.0>>

	* uni0162 (U+0162): L<<48.0,698.0>--<59.0,698.0>> -> L<<59.0,698.0>--<179.0,690.0>>

	* uni0162 (U+0162): L<<507.0,690.0>--<627.0,698.0>> -> L<<627.0,698.0>--<638.0,698.0>>

	* uni0162 (U+0162): L<<59.0,698.0>--<179.0,690.0>> -> L<<179.0,690.0>--<507.0,690.0>>

	* uni0163 (U+0163): L<<187.0,476.0>--<384.0,492.0>> -> L<<384.0,492.0>--<396.0,492.0>>

	* uni021A (U+021A): L<<179.0,690.0>--<507.0,690.0>> -> L<<507.0,690.0>--<627.0,698.0>>

	* uni021A (U+021A): L<<48.0,698.0>--<59.0,698.0>> -> L<<59.0,698.0>--<179.0,690.0>>

	* uni021A (U+021A): L<<507.0,690.0>--<627.0,698.0>> -> L<<627.0,698.0>--<638.0,698.0>>

	* uni021A (U+021A): L<<59.0,698.0>--<179.0,690.0>> -> L<<179.0,690.0>--<507.0,690.0>>

	* uni021B (U+021B): L<<187.0,476.0>--<384.0,492.0>> -> L<<384.0,492.0>--<396.0,492.0>>

	* uni1EB8 (U+1EB8): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* uni1EB8 (U+1EB8): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* uni1EBA (U+1EBA): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* uni1EBA (U+1EBA): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* uni1EBC (U+1EBC): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* uni1EBC (U+1EBC): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* uni1EBE (U+1EBE): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* uni1EBE (U+1EBE): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* uni1EC0 (U+1EC0): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* uni1EC0 (U+1EC0): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* uni1EC2 (U+1EC2): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* uni1EC2 (U+1EC2): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* uni1EC4 (U+1EC4): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* uni1EC4 (U+1EC4): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* uni1EC6 (U+1EC6): L<<30.0,690.0>--<432.0,690.0>> -> L<<432.0,690.0>--<545.0,698.0>>

	* uni1EC6 (U+1EC6): L<<432.0,690.0>--<545.0,698.0>> -> L<<545.0,698.0>--<556.0,698.0>>

	* uni20A9 (U+20A9): L<<348.0,82.0>--<348.0,82.0>> -> L<<348.0,82.0>--<348.0,82.0>> 

	* uni20A9 (U+20A9): L<<737.0,82.0>--<737.0,82.0>> -> L<<737.0,82.0>--<737.0,82.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[15] Platypi-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Version format is correct in 'name' table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/version_format">com.google.fonts/check/name/version_format</a>)</summary><div>


* 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000. Current version string is: "Version %d.%03d; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.33]" [code: bad-version-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1186 when it should be at least 1200 [code: bad-hhea-range]
* 🔥 **FAIL** The OS/2 sTypoDescender must be negative or zero. This font has a strictly positive value. [code: typo-descender]
* 🔥 **FAIL** The hhea descender must be negative or zero. This font has a strictly positive value. [code: hhea-descent]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Platypi-SemiBoldItalic.ttf', 'fonts/ttf/Platypi-ExtraBoldItalic.ttf', 'fonts/ttf/Platypi-LightItalic.ttf', 'fonts/ttf/Platypi-RegularItalic.ttf', 'fonts/ttf/Platypi-BoldItalic.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ j̦̓ į̆ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** name version string for platform 3, encoding 1 ("Version %d.%03d; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.33]"), could not be parsed. [code: parse]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'BOLT' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<282.0,690.0>--<731.0,690.0>> -> L<<731.0,690.0>--<851.0,699.0>>

	* AE (U+00C6): L<<731.0,690.0>--<851.0,699.0>> -> L<<851.0,699.0>--<864.0,699.0>>

	* AEacute (U+01FC): L<<282.0,690.0>--<731.0,690.0>> -> L<<731.0,690.0>--<851.0,699.0>>

	* AEacute (U+01FC): L<<731.0,690.0>--<851.0,699.0>> -> L<<851.0,699.0>--<864.0,699.0>>

	* B (U+0042): L<<220.0,389.0>--<248.0,389.0>> -> L<<248.0,389.0>--<343.0,392.0>>

	* E (U+0045): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* E (U+0045): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* Eacute (U+00C9): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* Eacute (U+00C9): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* Ebreve (U+0114): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* Ebreve (U+0114): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* Ecaron (U+011A): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* Ecaron (U+011A): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* Ecircumflex (U+00CA): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* Ecircumflex (U+00CA): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* Edieresis (U+00CB): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* Edieresis (U+00CB): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* Edotaccent (U+0116): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* Edotaccent (U+0116): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* Egrave (U+00C8): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* Egrave (U+00C8): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* Emacron (U+0112): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* Emacron (U+0112): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* Eogonek (U+0118): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* Eogonek (U+0118): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* F (U+0046): L<<29.0,690.0>--<414.0,690.0>> -> L<<414.0,690.0>--<535.0,699.0>>

	* F (U+0046): L<<414.0,690.0>--<535.0,699.0>> -> L<<535.0,699.0>--<548.0,699.0>>

	* OE (U+0152): L<<420.0,690.0>--<801.0,690.0>> -> L<<801.0,690.0>--<922.0,699.0>>

	* OE (U+0152): L<<801.0,690.0>--<922.0,699.0>> -> L<<922.0,699.0>--<935.0,699.0>>

	* T (U+0054): L<<185.0,690.0>--<512.0,690.0>> -> L<<512.0,690.0>--<638.0,699.0>>

	* T (U+0054): L<<46.0,699.0>--<59.0,699.0>> -> L<<59.0,699.0>--<185.0,690.0>>

	* T (U+0054): L<<512.0,690.0>--<638.0,699.0>> -> L<<638.0,699.0>--<652.0,699.0>>

	* T (U+0054): L<<59.0,699.0>--<185.0,690.0>> -> L<<185.0,690.0>--<512.0,690.0>>

	* Tbar (U+0166): L<<185.0,690.0>--<512.0,690.0>> -> L<<512.0,690.0>--<638.0,699.0>>

	* Tbar (U+0166): L<<46.0,699.0>--<59.0,699.0>> -> L<<59.0,699.0>--<185.0,690.0>>

	* Tbar (U+0166): L<<512.0,690.0>--<638.0,699.0>> -> L<<638.0,699.0>--<652.0,699.0>>

	* Tbar (U+0166): L<<59.0,699.0>--<185.0,690.0>> -> L<<185.0,690.0>--<512.0,690.0>>

	* Tcaron (U+0164): L<<185.0,690.0>--<512.0,690.0>> -> L<<512.0,690.0>--<638.0,699.0>>

	* Tcaron (U+0164): L<<46.0,699.0>--<59.0,699.0>> -> L<<59.0,699.0>--<185.0,690.0>>

	* Tcaron (U+0164): L<<512.0,690.0>--<638.0,699.0>> -> L<<638.0,699.0>--<652.0,699.0>>

	* Tcaron (U+0164): L<<59.0,699.0>--<185.0,690.0>> -> L<<185.0,690.0>--<512.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<185.0,690.0>--<512.0,690.0>> -> L<<512.0,690.0>--<638.0,699.0>>

	* Tmacronbelow (U+1E6E): L<<46.0,699.0>--<59.0,699.0>> -> L<<59.0,699.0>--<185.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<512.0,690.0>--<638.0,699.0>> -> L<<638.0,699.0>--<652.0,699.0>>

	* Tmacronbelow (U+1E6E): L<<59.0,699.0>--<185.0,690.0>> -> L<<185.0,690.0>--<512.0,690.0>>

	* Z (U+005A): L<<54.0,699.0>--<71.0,699.0>> -> L<<71.0,699.0>--<215.0,690.0>>

	* Z (U+005A): L<<71.0,699.0>--<215.0,690.0>> -> L<<215.0,690.0>--<584.0,690.0>>

	* Zacute (U+0179): L<<54.0,699.0>--<71.0,699.0>> -> L<<71.0,699.0>--<215.0,690.0>>

	* Zacute (U+0179): L<<71.0,699.0>--<215.0,690.0>> -> L<<215.0,690.0>--<584.0,690.0>>

	* Zcaron (U+017D): L<<54.0,699.0>--<71.0,699.0>> -> L<<71.0,699.0>--<215.0,690.0>>

	* Zcaron (U+017D): L<<71.0,699.0>--<215.0,690.0>> -> L<<215.0,690.0>--<584.0,690.0>>

	* Zdotaccent (U+017B): L<<54.0,699.0>--<71.0,699.0>> -> L<<71.0,699.0>--<215.0,690.0>>

	* Zdotaccent (U+017B): L<<71.0,699.0>--<215.0,690.0>> -> L<<215.0,690.0>--<584.0,690.0>>

	* fi (U+FB01): L<<220.0,471.0>--<559.0,492.0>> -> L<<559.0,492.0>--<584.0,492.0>>

	* trademark (U+2122): L<<10.0,695.0>--<70.0,690.0>> -> L<<70.0,690.0>--<200.0,690.0>>

	* trademark (U+2122): L<<2.0,695.0>--<10.0,695.0>> -> L<<10.0,695.0>--<70.0,690.0>>

	* trademark (U+2122): L<<200.0,690.0>--<259.0,695.0>> -> L<<259.0,695.0>--<268.0,695.0>>

	* trademark (U+2122): L<<70.0,690.0>--<200.0,690.0>> -> L<<200.0,690.0>--<259.0,695.0>>

	* uni0162 (U+0162): L<<185.0,690.0>--<512.0,690.0>> -> L<<512.0,690.0>--<638.0,699.0>>

	* uni0162 (U+0162): L<<46.0,699.0>--<59.0,699.0>> -> L<<59.0,699.0>--<185.0,690.0>>

	* uni0162 (U+0162): L<<512.0,690.0>--<638.0,699.0>> -> L<<638.0,699.0>--<652.0,699.0>>

	* uni0162 (U+0162): L<<59.0,699.0>--<185.0,690.0>> -> L<<185.0,690.0>--<512.0,690.0>>

	* uni021A (U+021A): L<<185.0,690.0>--<512.0,690.0>> -> L<<512.0,690.0>--<638.0,699.0>>

	* uni021A (U+021A): L<<46.0,699.0>--<59.0,699.0>> -> L<<59.0,699.0>--<185.0,690.0>>

	* uni021A (U+021A): L<<512.0,690.0>--<638.0,699.0>> -> L<<638.0,699.0>--<652.0,699.0>>

	* uni021A (U+021A): L<<59.0,699.0>--<185.0,690.0>> -> L<<185.0,690.0>--<512.0,690.0>>

	* uni0E3F (U+0E3F): L<<220.0,379.0>--<260.0,379.0>> -> L<<260.0,379.0>--<300.0,381.0>>

	* uni1EB8 (U+1EB8): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* uni1EB8 (U+1EB8): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* uni1EBA (U+1EBA): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* uni1EBA (U+1EBA): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* uni1EBC (U+1EBC): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* uni1EBC (U+1EBC): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* uni1EBE (U+1EBE): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* uni1EBE (U+1EBE): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* uni1EC0 (U+1EC0): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* uni1EC0 (U+1EC0): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* uni1EC2 (U+1EC2): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* uni1EC2 (U+1EC2): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* uni1EC4 (U+1EC4): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* uni1EC4 (U+1EC4): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>>

	* uni1EC6 (U+1EC6): L<<29.0,690.0>--<428.0,690.0>> -> L<<428.0,690.0>--<549.0,699.0>>

	* uni1EC6 (U+1EC6): L<<428.0,690.0>--<549.0,699.0>> -> L<<549.0,699.0>--<562.0,699.0>> 

	* uni20BF (U+20BF): L<<220.0,379.0>--<249.0,379.0>> -> L<<249.0,379.0>--<327.0,382.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[24] Platypi-ExtraBoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'Extra Bold Italic'. Expected OS/2 usWeightClass is 700, got 800. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Version format is correct in 'name' table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/version_format">com.google.fonts/check/name/version_format</a>)</summary><div>


* 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000. Current version string is: "Version 0.350; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.33]" [code: bad-version-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Platypi Extra Bold Italic | Platypi Extra |
| Subfamily Name | Regular | Bold Italic |
| Full Name | Platypi Extra Bold Italic | Platypi Extra Bold Italic |
| Poscript Name | Platypi-ExtraBoldItalic | PlatypiExtra-BoldItalic |
| Typographic Family Name | Platypi | N/A |
| Typographic Subfamily Name | Extra Bold Italic | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Platypi-SemiBoldItalic.ttf', 'fonts/ttf/Platypi-ExtraBoldItalic.ttf', 'fonts/ttf/Platypi-LightItalic.ttf', 'fonts/ttf/Platypi-RegularItalic.ttf', 'fonts/ttf/Platypi-BoldItalic.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1123, but got 965 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 342, but got 235 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (765) and hhea ascent (965) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle ITALIC bit should be set. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be unset. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection ITALIC bit should be set. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table IDs 1, 2, 16, 17 to conform to Italic style. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/name/italic_names">com.google.fonts/check/name/italic_names</a>)</summary><div>


* 🔥 **FAIL** Name ID 1 (Family Name) must not contain 'Italic'. [code: bad-familyname]
* 🔥 **FAIL** Name ID 2 (Subfamily Name) does not conform to specs. Only R/I/B/BI are allowed.
Got: 'Regular'. [code: bad-subfamilyname]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'BOLT' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Platypi Extra Bold Italic' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.TRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

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

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<298.0,690.0>--<750.0,690.0>> -> L<<750.0,690.0>--<902.0,698.0>>

	* AE (U+00C6): L<<750.0,690.0>--<902.0,698.0>> -> L<<902.0,698.0>--<921.0,698.0>>

	* AEacute (U+01FC): L<<298.0,690.0>--<750.0,690.0>> -> L<<750.0,690.0>--<902.0,698.0>>

	* AEacute (U+01FC): L<<750.0,690.0>--<902.0,698.0>> -> L<<902.0,698.0>--<921.0,698.0>>

	* E (U+0045): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* E (U+0045): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* Eacute (U+00C9): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* Eacute (U+00C9): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* Ebreve (U+0114): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* Ebreve (U+0114): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* Ecaron (U+011A): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* Ecaron (U+011A): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* Ecircumflex (U+00CA): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* Ecircumflex (U+00CA): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* Edieresis (U+00CB): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* Edieresis (U+00CB): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* Edotaccent (U+0116): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* Edotaccent (U+0116): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* Egrave (U+00C8): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* Egrave (U+00C8): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* Emacron (U+0112): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* Emacron (U+0112): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* Eogonek (U+0118): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* Eogonek (U+0118): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* F (U+0046): L<<120.0,690.0>--<481.0,690.0>> -> L<<481.0,690.0>--<633.0,698.0>>

	* F (U+0046): L<<481.0,690.0>--<633.0,698.0>> -> L<<633.0,698.0>--<652.0,698.0>>

	* K (U+004B): L<<860.0,668.0>--<721.0,590.0>> -> L<<721.0,590.0>--<506.0,445.0>>

	* OE (U+0152): L<<518.0,690.0>--<884.0,690.0>> -> L<<884.0,690.0>--<1036.0,698.0>>

	* OE (U+0152): L<<884.0,690.0>--<1036.0,698.0>> -> L<<1036.0,698.0>--<1055.0,698.0>>

	* T (U+0054): L<<129.0,698.0>--<148.0,698.0>> -> L<<148.0,698.0>--<289.0,690.0>>

	* T (U+0054): L<<148.0,698.0>--<289.0,690.0>> -> L<<289.0,690.0>--<591.0,690.0>>

	* T (U+0054): L<<289.0,690.0>--<591.0,690.0>> -> L<<591.0,690.0>--<760.0,698.0>>

	* T (U+0054): L<<591.0,690.0>--<760.0,698.0>> -> L<<760.0,698.0>--<780.0,698.0>>

	* Tcaron (U+0164): L<<129.0,698.0>--<148.0,698.0>> -> L<<148.0,698.0>--<289.0,690.0>>

	* Tcaron (U+0164): L<<148.0,698.0>--<289.0,690.0>> -> L<<289.0,690.0>--<591.0,690.0>>

	* Tcaron (U+0164): L<<289.0,690.0>--<591.0,690.0>> -> L<<591.0,690.0>--<760.0,698.0>>

	* Tcaron (U+0164): L<<591.0,690.0>--<760.0,698.0>> -> L<<760.0,698.0>--<780.0,698.0>>

	* Tmacronbelow (U+1E6E): L<<129.0,698.0>--<148.0,698.0>> -> L<<148.0,698.0>--<289.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<148.0,698.0>--<289.0,690.0>> -> L<<289.0,690.0>--<591.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<289.0,690.0>--<591.0,690.0>> -> L<<591.0,690.0>--<760.0,698.0>>

	* Tmacronbelow (U+1E6E): L<<591.0,690.0>--<760.0,698.0>> -> L<<760.0,698.0>--<780.0,698.0>>

	* X (U+0058): L<<830.0,668.0>--<747.0,606.0>> -> L<<747.0,606.0>--<501.0,383.0>>

	* Z (U+005A): L<<131.0,706.0>--<151.0,706.0>> -> L<<151.0,706.0>--<320.0,690.0>>

	* Z (U+005A): L<<151.0,706.0>--<320.0,690.0>> -> L<<320.0,690.0>--<689.0,690.0>>

	* Zacute (U+0179): L<<131.0,706.0>--<151.0,706.0>> -> L<<151.0,706.0>--<320.0,690.0>>

	* Zacute (U+0179): L<<151.0,706.0>--<320.0,690.0>> -> L<<320.0,690.0>--<689.0,690.0>>

	* Zcaron (U+017D): L<<131.0,706.0>--<151.0,706.0>> -> L<<151.0,706.0>--<320.0,690.0>>

	* Zcaron (U+017D): L<<151.0,706.0>--<320.0,690.0>> -> L<<320.0,690.0>--<689.0,690.0>>

	* Zdotaccent (U+017B): L<<131.0,706.0>--<151.0,706.0>> -> L<<151.0,706.0>--<320.0,690.0>>

	* Zdotaccent (U+017B): L<<151.0,706.0>--<320.0,690.0>> -> L<<320.0,690.0>--<689.0,690.0>>

	* three (U+0033): L<<311.0,326.0>--<321.0,364.0>> -> L<<321.0,364.0>--<330.0,398.0>>

	* trademark (U+2122): L<<135.0,696.0>--<145.0,696.0>> -> L<<145.0,696.0>--<205.0,690.0>>

	* trademark (U+2122): L<<145.0,696.0>--<205.0,690.0>> -> L<<205.0,690.0>--<339.0,690.0>>

	* trademark (U+2122): L<<205.0,690.0>--<339.0,690.0>> -> L<<339.0,690.0>--<401.0,696.0>>

	* trademark (U+2122): L<<339.0,690.0>--<401.0,696.0>> -> L<<401.0,696.0>--<411.0,696.0>>

	* uni0136 (U+0136): L<<860.0,668.0>--<721.0,590.0>> -> L<<721.0,590.0>--<506.0,445.0>>

	* uni021A (U+021A): L<<129.0,698.0>--<148.0,698.0>> -> L<<148.0,698.0>--<289.0,690.0>>

	* uni021A (U+021A): L<<148.0,698.0>--<289.0,690.0>> -> L<<289.0,690.0>--<591.0,690.0>>

	* uni021A (U+021A): L<<289.0,690.0>--<591.0,690.0>> -> L<<591.0,690.0>--<760.0,698.0>>

	* uni021A (U+021A): L<<591.0,690.0>--<760.0,698.0>> -> L<<760.0,698.0>--<780.0,698.0>>

	* uni1EB8 (U+1EB8): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* uni1EB8 (U+1EB8): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* uni1EBA (U+1EBA): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* uni1EBA (U+1EBA): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* uni1EBC (U+1EBC): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* uni1EBC (U+1EBC): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* uni1EBE (U+1EBE): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* uni1EBE (U+1EBE): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* uni1EC0 (U+1EC0): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* uni1EC0 (U+1EC0): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* uni1EC2 (U+1EC2): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* uni1EC2 (U+1EC2): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* uni1EC4 (U+1EC4): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>>

	* uni1EC4 (U+1EC4): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>>

	* uni1EC6 (U+1EC6): L<<120.0,690.0>--<486.0,690.0>> -> L<<486.0,690.0>--<638.0,698.0>> 

	* uni1EC6 (U+1EC6): L<<486.0,690.0>--<638.0,698.0>> -> L<<638.0,698.0>--<657.0,698.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[16] Platypi-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Version format is correct in 'name' table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/version_format">com.google.fonts/check/name/version_format</a>)</summary><div>


* 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000. Current version string is: "Version %d.%03d; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.33]" [code: bad-version-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1186 when it should be at least 1200 [code: bad-hhea-range]
* 🔥 **FAIL** The OS/2 sTypoDescender must be negative or zero. This font has a strictly positive value. [code: typo-descender]
* 🔥 **FAIL** The hhea descender must be negative or zero. This font has a strictly positive value. [code: hhea-descent]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Platypi-SemiBoldItalic.ttf', 'fonts/ttf/Platypi-ExtraBoldItalic.ttf', 'fonts/ttf/Platypi-LightItalic.ttf', 'fonts/ttf/Platypi-RegularItalic.ttf', 'fonts/ttf/Platypi-BoldItalic.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ j̦̓ į̆ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** name version string for platform 3, encoding 1 ("Version %d.%03d; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.33]"), could not be parsed. [code: parse]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'BOLT' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<292.0,690.0>--<762.0,690.0>> -> L<<762.0,690.0>--<910.0,704.0>>

	* AE (U+00C6): L<<762.0,690.0>--<910.0,704.0>> -> L<<910.0,704.0>--<928.0,704.0>>

	* AEacute (U+01FC): L<<292.0,690.0>--<762.0,690.0>> -> L<<762.0,690.0>--<910.0,704.0>>

	* AEacute (U+01FC): L<<762.0,690.0>--<910.0,704.0>> -> L<<910.0,704.0>--<928.0,704.0>>

	* E (U+0045): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* E (U+0045): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* Eacute (U+00C9): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* Eacute (U+00C9): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* Ebreve (U+0114): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* Ebreve (U+0114): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* Ecaron (U+011A): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* Ecaron (U+011A): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* Ecircumflex (U+00CA): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* Ecircumflex (U+00CA): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* Edieresis (U+00CB): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* Edieresis (U+00CB): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* Edotaccent (U+0116): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* Edotaccent (U+0116): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* Egrave (U+00C8): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* Egrave (U+00C8): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* Emacron (U+0112): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* Emacron (U+0112): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* Eogonek (U+0118): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* Eogonek (U+0118): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* F (U+0046): L<<27.0,690.0>--<405.0,690.0>> -> L<<405.0,690.0>--<552.0,704.0>>

	* F (U+0046): L<<405.0,690.0>--<552.0,704.0>> -> L<<552.0,704.0>--<570.0,704.0>>

	* OE (U+0152): L<<443.0,690.0>--<809.0,690.0>> -> L<<809.0,690.0>--<956.0,704.0>>

	* OE (U+0152): L<<809.0,690.0>--<956.0,704.0>> -> L<<956.0,704.0>--<974.0,704.0>>

	* T (U+0054): L<<206.0,690.0>--<530.0,690.0>> -> L<<530.0,690.0>--<676.0,704.0>>

	* T (U+0054): L<<38.0,704.0>--<60.0,704.0>> -> L<<60.0,704.0>--<206.0,690.0>>

	* T (U+0054): L<<530.0,690.0>--<676.0,704.0>> -> L<<676.0,704.0>--<698.0,704.0>>

	* T (U+0054): L<<60.0,704.0>--<206.0,690.0>> -> L<<206.0,690.0>--<530.0,690.0>>

	* Tbar (U+0166): L<<206.0,690.0>--<530.0,690.0>> -> L<<530.0,690.0>--<676.0,704.0>>

	* Tbar (U+0166): L<<38.0,704.0>--<60.0,704.0>> -> L<<60.0,704.0>--<206.0,690.0>>

	* Tbar (U+0166): L<<530.0,690.0>--<676.0,704.0>> -> L<<676.0,704.0>--<698.0,704.0>>

	* Tbar (U+0166): L<<60.0,704.0>--<206.0,690.0>> -> L<<206.0,690.0>--<530.0,690.0>>

	* Tcaron (U+0164): L<<206.0,690.0>--<530.0,690.0>> -> L<<530.0,690.0>--<676.0,704.0>>

	* Tcaron (U+0164): L<<38.0,704.0>--<60.0,704.0>> -> L<<60.0,704.0>--<206.0,690.0>>

	* Tcaron (U+0164): L<<530.0,690.0>--<676.0,704.0>> -> L<<676.0,704.0>--<698.0,704.0>>

	* Tcaron (U+0164): L<<60.0,704.0>--<206.0,690.0>> -> L<<206.0,690.0>--<530.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<206.0,690.0>--<530.0,690.0>> -> L<<530.0,690.0>--<676.0,704.0>>

	* Tmacronbelow (U+1E6E): L<<38.0,704.0>--<60.0,704.0>> -> L<<60.0,704.0>--<206.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<530.0,690.0>--<676.0,704.0>> -> L<<676.0,704.0>--<698.0,704.0>>

	* Tmacronbelow (U+1E6E): L<<60.0,704.0>--<206.0,690.0>> -> L<<206.0,690.0>--<530.0,690.0>>

	* Z (U+005A): L<<47.0,704.0>--<66.0,704.0>> -> L<<66.0,704.0>--<227.0,690.0>>

	* Z (U+005A): L<<66.0,704.0>--<227.0,690.0>> -> L<<227.0,690.0>--<625.0,690.0>>

	* Zacute (U+0179): L<<47.0,704.0>--<66.0,704.0>> -> L<<66.0,704.0>--<227.0,690.0>>

	* Zacute (U+0179): L<<66.0,704.0>--<227.0,690.0>> -> L<<227.0,690.0>--<625.0,690.0>>

	* Zcaron (U+017D): L<<47.0,704.0>--<66.0,704.0>> -> L<<66.0,704.0>--<227.0,690.0>>

	* Zcaron (U+017D): L<<66.0,704.0>--<227.0,690.0>> -> L<<227.0,690.0>--<625.0,690.0>>

	* Zdotaccent (U+017B): L<<47.0,704.0>--<66.0,704.0>> -> L<<66.0,704.0>--<227.0,690.0>>

	* Zdotaccent (U+017B): L<<66.0,704.0>--<227.0,690.0>> -> L<<227.0,690.0>--<625.0,690.0>>

	* fi (U+FB01): L<<265.0,477.0>--<625.0,507.0>> -> L<<625.0,507.0>--<656.0,507.0>>

	* trademark (U+2122): L<<12.0,696.0>--<72.0,690.0>> -> L<<72.0,690.0>--<205.0,690.0>>

	* trademark (U+2122): L<<2.0,696.0>--<12.0,696.0>> -> L<<12.0,696.0>--<72.0,690.0>>

	* trademark (U+2122): L<<205.0,690.0>--<266.0,696.0>> -> L<<266.0,696.0>--<275.0,696.0>>

	* trademark (U+2122): L<<72.0,690.0>--<205.0,690.0>> -> L<<205.0,690.0>--<266.0,696.0>>

	* uni0162 (U+0162): L<<206.0,690.0>--<530.0,690.0>> -> L<<530.0,690.0>--<676.0,704.0>>

	* uni0162 (U+0162): L<<38.0,704.0>--<60.0,704.0>> -> L<<60.0,704.0>--<206.0,690.0>>

	* uni0162 (U+0162): L<<530.0,690.0>--<676.0,704.0>> -> L<<676.0,704.0>--<698.0,704.0>>

	* uni0162 (U+0162): L<<60.0,704.0>--<206.0,690.0>> -> L<<206.0,690.0>--<530.0,690.0>>

	* uni021A (U+021A): L<<206.0,690.0>--<530.0,690.0>> -> L<<530.0,690.0>--<676.0,704.0>>

	* uni021A (U+021A): L<<38.0,704.0>--<60.0,704.0>> -> L<<60.0,704.0>--<206.0,690.0>>

	* uni021A (U+021A): L<<530.0,690.0>--<676.0,704.0>> -> L<<676.0,704.0>--<698.0,704.0>>

	* uni021A (U+021A): L<<60.0,704.0>--<206.0,690.0>> -> L<<206.0,690.0>--<530.0,690.0>>

	* uni1EB8 (U+1EB8): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* uni1EB8 (U+1EB8): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* uni1EBA (U+1EBA): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* uni1EBA (U+1EBA): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* uni1EBC (U+1EBC): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* uni1EBC (U+1EBC): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* uni1EBE (U+1EBE): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* uni1EBE (U+1EBE): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* uni1EC0 (U+1EC0): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* uni1EC0 (U+1EC0): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* uni1EC2 (U+1EC2): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* uni1EC2 (U+1EC2): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* uni1EC4 (U+1EC4): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>>

	* uni1EC4 (U+1EC4): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>>

	* uni1EC6 (U+1EC6): L<<27.0,690.0>--<416.0,690.0>> -> L<<416.0,690.0>--<563.0,704.0>> 

	* uni1EC6 (U+1EC6): L<<416.0,690.0>--<563.0,704.0>> -> L<<563.0,704.0>--<581.0,704.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<928.0,704.0>--<929.0,524.0>>

	* AEacute (U+01FC): L<<928.0,704.0>--<929.0,524.0>>

	* E (U+0045): L<<581.0,704.0>--<582.0,524.0>>

	* Eacute (U+00C9): L<<581.0,704.0>--<582.0,524.0>>

	* Ebreve (U+0114): L<<581.0,704.0>--<582.0,524.0>>

	* Ecaron (U+011A): L<<581.0,704.0>--<582.0,524.0>>

	* Ecircumflex (U+00CA): L<<581.0,704.0>--<582.0,524.0>>

	* Edieresis (U+00CB): L<<581.0,704.0>--<582.0,524.0>>

	* Edotaccent (U+0116): L<<581.0,704.0>--<582.0,524.0>>

	* Egrave (U+00C8): L<<581.0,704.0>--<582.0,524.0>>

	* Emacron (U+0112): L<<581.0,704.0>--<582.0,524.0>>

	* Eogonek (U+0118): L<<581.0,704.0>--<582.0,524.0>>

	* F (U+0046): L<<570.0,704.0>--<571.0,524.0>>

	* L (U+004C): L<<580.0,212.0>--<579.0,0.0>>

	* Lacute (U+0139): L<<580.0,212.0>--<579.0,0.0>>

	* Lcaron (U+013D): L<<580.0,212.0>--<579.0,0.0>>

	* Ldot (U+013F): L<<580.0,212.0>--<579.0,0.0>>

	* Lmacronbelow (U+1E3A): L<<580.0,212.0>--<579.0,0.0>>

	* Lslash (U+0141): L<<580.0,212.0>--<579.0,0.0>>

	* asterisk (U+002A): L<<162.0,560.0>--<13.0,561.0>>

	* asterisk (U+002A): L<<412.0,561.0>--<263.0,560.0>>

	* uni013B (U+013B): L<<580.0,212.0>--<579.0,0.0>>

	* uni1EB8 (U+1EB8): L<<581.0,704.0>--<582.0,524.0>>

	* uni1EBA (U+1EBA): L<<581.0,704.0>--<582.0,524.0>>

	* uni1EBC (U+1EBC): L<<581.0,704.0>--<582.0,524.0>>

	* uni1EBE (U+1EBE): L<<581.0,704.0>--<582.0,524.0>>

	* uni1EC0 (U+1EC0): L<<581.0,704.0>--<582.0,524.0>>

	* uni1EC2 (U+1EC2): L<<581.0,704.0>--<582.0,524.0>>

	* uni1EC4 (U+1EC4): L<<581.0,704.0>--<582.0,524.0>> 

	* uni1EC6 (U+1EC6): L<<581.0,704.0>--<582.0,524.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[23] Platypi-LightItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Version format is correct in 'name' table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/version_format">com.google.fonts/check/name/version_format</a>)</summary><div>


* 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000. Current version string is: "Version 0.350; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.33]" [code: bad-version-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Platypi Light Italic | Platypi Light |
| Subfamily Name | Regular | Italic |
| Full Name | Platypi Light Italic | Platypi Light Italic |
| Poscript Name | Platypi-LightItalic | Platypi-LightItalic |
| Typographic Family Name | Platypi | Platypi |
| Typographic Subfamily Name | Light Italic | Light Italic | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Platypi-SemiBoldItalic.ttf', 'fonts/ttf/Platypi-ExtraBoldItalic.ttf', 'fonts/ttf/Platypi-LightItalic.ttf', 'fonts/ttf/Platypi-RegularItalic.ttf', 'fonts/ttf/Platypi-BoldItalic.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1123, but got 965 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 342, but got 235 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (765) and hhea ascent (965) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle ITALIC bit should be set. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be unset. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection ITALIC bit should be set. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table IDs 1, 2, 16, 17 to conform to Italic style. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/name/italic_names">com.google.fonts/check/name/italic_names</a>)</summary><div>


* 🔥 **FAIL** Name ID 1 (Family Name) must not contain 'Italic'. [code: bad-familyname]
* 🔥 **FAIL** Name ID 2 (Subfamily Name) does not conform to specs. Only R/I/B/BI are allowed.
Got: 'Regular'. [code: bad-subfamilyname]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'BOLT' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.TRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

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

	- Glyph name: uni019D	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni019D	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=248.5,Y=688.0 (should be at cap-height 690?)

	* six (U+0036): X=544.5,Y=688.0 (should be at cap-height 690?)

	* question (U+003F): X=228.0,Y=691.5 (should be at cap-height 690?)

	* at (U+0040): X=468.5,Y=692.0 (should be at cap-height 690?)

	* at (U+0040): X=105.5,Y=0.5 (should be at baseline 0?)

	* at (U+0040): X=803.0,Y=1.0 (should be at baseline 0?)

	* bracketleft (U+005B): X=264.0,Y=692.0 (should be at cap-height 690?)

	* bracketright (U+005D): X=231.0,Y=692.0 (should be at cap-height 690?)

	* g (U+0067): X=6.5,Y=-237.0 (should be at descender -235?)

	* g (U+0067): X=478.0,Y=478.0 (should be at x-height 480?)

	* section (U+00A7): X=272.0,Y=690.5 (should be at cap-height 690?)

	* acute (U+00B4): X=339.0,Y=692.0 (should be at cap-height 690?)

	* cedilla (U+00B8): X=109.5,Y=-233.5 (should be at descender -235?)

	* Atilde (U+00C3): X=221.0,Y=764.0 (should be at ascender 765?)

	* Aring (U+00C5): X=481.0,Y=763.0 (should be at ascender 765?)

	* Aring (U+00C5): X=399.0,Y=767.0 (should be at ascender 765?)

	* Aring (U+00C5): X=399.0,Y=767.0 (should be at ascender 765?)

	* Ccedilla (U+00C7): X=286.5,Y=-233.5 (should be at descender -235?)

	* Ntilde (U+00D1): X=247.0,Y=764.0 (should be at ascender 765?)

	* Otilde (U+00D5): X=294.0,Y=764.0 (should be at ascender 765?)

	* aacute (U+00E1): X=534.0,Y=692.0 (should be at cap-height 690?)

	* ccedilla (U+00E7): X=198.5,Y=-233.5 (should be at descender -235?)

	* eacute (U+00E9): X=499.0,Y=692.0 (should be at cap-height 690?)

	* oacute (U+00F3): X=514.0,Y=692.0 (should be at cap-height 690?)

	* uacute (U+00FA): X=527.0,Y=692.0 (should be at cap-height 690?)

	* yacute (U+00FD): X=473.0,Y=692.0 (should be at cap-height 690?)

	* Aogonek (U+0104): X=481.0,Y=-2.0 (should be at baseline 0?)

	* cacute (U+0107): X=504.0,Y=692.0 (should be at cap-height 690?)

	* Cdotaccent (U+010A): X=411.0,Y=763.0 (should be at ascender 765?)

	* dcaron (U+010F): X=625.0,Y=766.0 (should be at ascender 765?)

	* dcaron (U+010F): X=628.0,Y=766.0 (should be at ascender 765?)

	* Edotaccent (U+0116): X=377.0,Y=763.0 (should be at ascender 765?)

	* Eogonek (U+0118): X=365.0,Y=-2.0 (should be at baseline 0?)

	* gcircumflex (U+011D): X=6.5,Y=-237.0 (should be at descender -235?)

	* gbreve (U+011F): X=6.5,Y=-237.0 (should be at descender -235?)

	* Gdotaccent (U+0120): X=420.0,Y=763.0 (should be at ascender 765?)

	* gdotaccent (U+0121): X=6.5,Y=-237.0 (should be at descender -235?)

	* uni0123 (U+0123): X=6.5,Y=-237.0 (should be at descender -235?)

	* Itilde (U+0128): X=82.0,Y=764.0 (should be at ascender 765?)

	* Iogonek (U+012E): X=74.0,Y=-2.0 (should be at baseline 0?)

	* Idotaccent (U+0130): X=222.0,Y=763.0 (should be at ascender 765?)

	* Lcaron (U+013D): X=431.0,Y=691.0 (should be at cap-height 690?)

	* Lcaron (U+013D): X=434.0,Y=691.0 (should be at cap-height 690?)

	* lcaron (U+013E): X=346.0,Y=766.0 (should be at ascender 765?)

	* lcaron (U+013E): X=349.0,Y=766.0 (should be at ascender 765?)

	* nacute (U+0144): X=562.0,Y=692.0 (should be at cap-height 690?)

	* racute (U+0155): X=476.0,Y=692.0 (should be at cap-height 690?)

	* sacute (U+015B): X=468.0,Y=692.0 (should be at cap-height 690?)

	* Scedilla (U+015E): X=266.5,Y=-233.5 (should be at descender -235?)

	* scedilla (U+015F): X=192.5,Y=-233.5 (should be at descender -235?)

	* tcaron (U+0165): X=340.0,Y=766.0 (should be at ascender 765?)

	* tcaron (U+0165): X=343.0,Y=766.0 (should be at ascender 765?)

	* Utilde (U+0168): X=289.0,Y=764.0 (should be at ascender 765?)

	* Uring (U+016E): X=549.0,Y=763.0 (should be at ascender 765?)

	* Uring (U+016E): X=467.0,Y=767.0 (should be at ascender 765?)

	* Uring (U+016E): X=467.0,Y=767.0 (should be at ascender 765?)

	* Uogonek (U+0172): X=307.0,Y=-2.0 (should be at baseline 0?)

	* zacute (U+017A): X=495.0,Y=692.0 (should be at cap-height 690?)

	* Zdotaccent (U+017B): X=349.0,Y=763.0 (should be at ascender 765?)

	* uni018F (U+018F): X=232.5,Y=692.0 (should be at cap-height 690?)

	* gcaron (U+01E7): X=6.5,Y=-237.0 (should be at descender -235?)

	* aeacute (U+01FD): X=679.0,Y=692.0 (should be at cap-height 690?)

	* oslashacute (U+01FF): X=514.0,Y=692.0 (should be at cap-height 690?)

	* acutecomb (U+0301): X=339.0,Y=692.0 (should be at cap-height 690?)

	* uni0327 (U+0327): X=109.5,Y=-233.5 (should be at descender -235?)

	* uni0338 (U+0338): X=21.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=631.0,Y=692.0 (should be at cap-height 690?)

	* uni1EA2 (U+1EA2): X=329.0,Y=763.0 (should be at ascender 765?)

	* uni1EA5 (U+1EA5): X=477.0,Y=689.0 (should be at cap-height 690?)

	* uni1EAF (U+1EAF): X=341.0,Y=689.0 (should be at cap-height 690?)

	* uni1EB3 (U+1EB3): X=402.0,Y=766.0 (should be at ascender 765?)

	* uni1EBA (U+1EBA): X=345.0,Y=763.0 (should be at ascender 765?)

	* uni1EBC (U+1EBC): X=237.0,Y=764.0 (should be at ascender 765?)

	* uni1EBF (U+1EBF): X=442.0,Y=689.0 (should be at cap-height 690?)

	* uni1EC8 (U+1EC8): X=190.0,Y=763.0 (should be at ascender 765?)

	* uni1ECE (U+1ECE): X=402.0,Y=763.0 (should be at ascender 765?)

	* uni1ED1 (U+1ED1): X=457.0,Y=689.0 (should be at cap-height 690?)

	* uni1EDB (U+1EDB): X=514.0,Y=692.0 (should be at cap-height 690?)

	* uni1EDE (U+1EDE): X=402.0,Y=763.0 (should be at ascender 765?)

	* uni1EE6 (U+1EE6): X=397.0,Y=763.0 (should be at ascender 765?)

	* uni1EE9 (U+1EE9): X=527.0,Y=692.0 (should be at cap-height 690?)

	* uni1EEC (U+1EEC): X=397.0,Y=763.0 (should be at ascender 765?)

	* uni1EF6 (U+1EF6): X=363.0,Y=763.0 (should be at ascender 765?) 

	* uni1EF8 (U+1EF8): X=255.0,Y=764.0 (should be at ascender 765?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<265.0,690.0>--<696.0,690.0>> -> L<<696.0,690.0>--<810.0,698.0>>

	* AE (U+00C6): L<<696.0,690.0>--<810.0,698.0>> -> L<<810.0,698.0>--<821.0,698.0>>

	* AEacute (U+01FC): L<<265.0,690.0>--<696.0,690.0>> -> L<<696.0,690.0>--<810.0,698.0>>

	* AEacute (U+01FC): L<<696.0,690.0>--<810.0,698.0>> -> L<<810.0,698.0>--<821.0,698.0>>

	* E (U+0045): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* E (U+0045): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* Eacute (U+00C9): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* Eacute (U+00C9): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* Ebreve (U+0114): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* Ebreve (U+0114): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* Ecaron (U+011A): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* Ecaron (U+011A): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* Ecircumflex (U+00CA): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* Ecircumflex (U+00CA): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* Edieresis (U+00CB): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* Edieresis (U+00CB): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* Edotaccent (U+0116): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* Edotaccent (U+0116): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* Egrave (U+00C8): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* Egrave (U+00C8): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* Emacron (U+0112): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* Emacron (U+0112): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* Eogonek (U+0118): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* Eogonek (U+0118): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* F (U+0046): L<<126.0,690.0>--<479.0,690.0>> -> L<<479.0,690.0>--<593.0,698.0>>

	* F (U+0046): L<<479.0,690.0>--<593.0,698.0>> -> L<<593.0,698.0>--<604.0,698.0>>

	* K (U+004B): L<<741.0,674.0>--<616.0,595.0>> -> L<<616.0,595.0>--<391.0,434.0>>

	* OE (U+0152): L<<513.0,690.0>--<849.0,690.0>> -> L<<849.0,690.0>--<963.0,698.0>>

	* OE (U+0152): L<<849.0,690.0>--<963.0,698.0>> -> L<<963.0,698.0>--<974.0,698.0>>

	* T (U+0054): L<<140.0,698.0>--<151.0,698.0>> -> L<<151.0,698.0>--<266.0,690.0>>

	* T (U+0054): L<<151.0,698.0>--<266.0,690.0>> -> L<<266.0,690.0>--<581.0,690.0>>

	* T (U+0054): L<<266.0,690.0>--<581.0,690.0>> -> L<<581.0,690.0>--<704.0,698.0>>

	* T (U+0054): L<<581.0,690.0>--<704.0,698.0>> -> L<<704.0,698.0>--<715.0,698.0>>

	* Tcaron (U+0164): L<<140.0,698.0>--<151.0,698.0>> -> L<<151.0,698.0>--<266.0,690.0>>

	* Tcaron (U+0164): L<<151.0,698.0>--<266.0,690.0>> -> L<<266.0,690.0>--<581.0,690.0>>

	* Tcaron (U+0164): L<<266.0,690.0>--<581.0,690.0>> -> L<<581.0,690.0>--<704.0,698.0>>

	* Tcaron (U+0164): L<<581.0,690.0>--<704.0,698.0>> -> L<<704.0,698.0>--<715.0,698.0>>

	* Tmacronbelow (U+1E6E): L<<140.0,698.0>--<151.0,698.0>> -> L<<151.0,698.0>--<266.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<151.0,698.0>--<266.0,690.0>> -> L<<266.0,690.0>--<581.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<266.0,690.0>--<581.0,690.0>> -> L<<581.0,690.0>--<704.0,698.0>>

	* Tmacronbelow (U+1E6E): L<<581.0,690.0>--<704.0,698.0>> -> L<<704.0,698.0>--<715.0,698.0>>

	* Z (U+005A): L<<140.0,698.0>--<151.0,698.0>> -> L<<151.0,698.0>--<261.0,690.0>>

	* Z (U+005A): L<<151.0,698.0>--<261.0,690.0>> -> L<<261.0,690.0>--<618.0,690.0>>

	* Zacute (U+0179): L<<140.0,698.0>--<151.0,698.0>> -> L<<151.0,698.0>--<261.0,690.0>>

	* Zacute (U+0179): L<<151.0,698.0>--<261.0,690.0>> -> L<<261.0,690.0>--<618.0,690.0>>

	* Zcaron (U+017D): L<<140.0,698.0>--<151.0,698.0>> -> L<<151.0,698.0>--<261.0,690.0>>

	* Zcaron (U+017D): L<<151.0,698.0>--<261.0,690.0>> -> L<<261.0,690.0>--<618.0,690.0>>

	* Zdotaccent (U+017B): L<<140.0,698.0>--<151.0,698.0>> -> L<<151.0,698.0>--<261.0,690.0>>

	* Zdotaccent (U+017B): L<<151.0,698.0>--<261.0,690.0>> -> L<<261.0,690.0>--<618.0,690.0>>

	* t (U+0074): L<<211.0,475.0>--<396.0,492.0>> -> L<<396.0,492.0>--<408.0,492.0>>

	* tcaron (U+0165): L<<211.0,475.0>--<396.0,492.0>> -> L<<396.0,492.0>--<408.0,492.0>>

	* tmacronbelow (U+1E6F): L<<211.0,475.0>--<396.0,492.0>> -> L<<396.0,492.0>--<408.0,492.0>>

	* trademark (U+2122): L<<147.0,695.0>--<155.0,695.0>> -> L<<155.0,695.0>--<213.0,690.0>>

	* trademark (U+2122): L<<155.0,695.0>--<213.0,690.0>> -> L<<213.0,690.0>--<343.0,690.0>>

	* trademark (U+2122): L<<213.0,690.0>--<343.0,690.0>> -> L<<343.0,690.0>--<402.0,695.0>>

	* trademark (U+2122): L<<343.0,690.0>--<402.0,695.0>> -> L<<402.0,695.0>--<411.0,695.0>>

	* uni00B5 (U+00B5): L<<-25.0,-238.0>--<88.0,158.0>> -> L<<88.0,158.0>--<89.0,163.0>>

	* uni00B5 (U+00B5): L<<88.0,158.0>--<89.0,163.0>> -> L<<89.0,163.0>--<143.0,353.0>>

	* uni0136 (U+0136): L<<741.0,674.0>--<616.0,595.0>> -> L<<616.0,595.0>--<391.0,434.0>>

	* uni021A (U+021A): L<<140.0,698.0>--<151.0,698.0>> -> L<<151.0,698.0>--<266.0,690.0>>

	* uni021A (U+021A): L<<151.0,698.0>--<266.0,690.0>> -> L<<266.0,690.0>--<581.0,690.0>>

	* uni021A (U+021A): L<<266.0,690.0>--<581.0,690.0>> -> L<<581.0,690.0>--<704.0,698.0>>

	* uni021A (U+021A): L<<581.0,690.0>--<704.0,698.0>> -> L<<704.0,698.0>--<715.0,698.0>>

	* uni021B (U+021B): L<<211.0,475.0>--<396.0,492.0>> -> L<<396.0,492.0>--<408.0,492.0>>

	* uni1EB8 (U+1EB8): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* uni1EB8 (U+1EB8): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* uni1EBA (U+1EBA): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* uni1EBA (U+1EBA): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* uni1EBC (U+1EBC): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* uni1EBC (U+1EBC): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* uni1EBE (U+1EBE): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* uni1EBE (U+1EBE): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* uni1EC0 (U+1EC0): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* uni1EC0 (U+1EC0): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* uni1EC2 (U+1EC2): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* uni1EC2 (U+1EC2): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* uni1EC4 (U+1EC4): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>>

	* uni1EC4 (U+1EC4): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>>

	* uni1EC6 (U+1EC6): L<<126.0,690.0>--<498.0,690.0>> -> L<<498.0,690.0>--<612.0,698.0>> 

	* uni1EC6 (U+1EC6): L<<498.0,690.0>--<612.0,698.0>> -> L<<612.0,698.0>--<623.0,698.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[19] Platypi-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'Extra Bold'. Expected OS/2 usWeightClass is 700, got 800. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Version format is correct in 'name' table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/version_format">com.google.fonts/check/name/version_format</a>)</summary><div>


* 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000. Current version string is: "Version %d.%03d; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.33]" [code: bad-version-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Platypi Extra Bold | Platypi Extra |
| Subfamily Name | Regular | Bold |
| Full Name | Platypi Extra Bold | Platypi Extra Bold |
| Poscript Name | Platypi-ExtraBold | PlatypiExtra-Bold |
| Typographic Family Name | Platypi | N/A |
| Typographic Subfamily Name | Extra Bold | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1186 when it should be at least 1200 [code: bad-hhea-range]
* 🔥 **FAIL** The OS/2 sTypoDescender must be negative or zero. This font has a strictly positive value. [code: typo-descender]
* 🔥 **FAIL** The hhea descender must be negative or zero. This font has a strictly positive value. [code: hhea-descent]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Platypi-SemiBoldItalic.ttf', 'fonts/ttf/Platypi-ExtraBoldItalic.ttf', 'fonts/ttf/Platypi-LightItalic.ttf', 'fonts/ttf/Platypi-RegularItalic.ttf', 'fonts/ttf/Platypi-BoldItalic.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ j̦̓ į̆ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** name version string for platform 3, encoding 1 ("Version %d.%03d; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.33]"), could not be parsed. [code: parse]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'BOLT' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=275.0,Y=688.0 (should be at cap-height 690?)

	* ampersand (U+0026): X=491.5,Y=689.5 (should be at cap-height 690?)

	* ampersand (U+0026): X=690.5,Y=252.0 (should be at descender 251?)

	* ampersand (U+0026): X=224.0,Y=249.0 (should be at descender 251?)

	* ampersand (U+0026): X=224.0,Y=249.0 (should be at descender 251?)

	* five (U+0035): X=168.0,Y=1.5 (should be at baseline 0?)

	* nine (U+0039): X=281.0,Y=252.0 (should be at descender 251?)

	* at (U+0040): X=215.0,Y=250.0 (should be at descender 251?)

	* G (U+0047): X=496.5,Y=1.0 (should be at baseline 0?)

	* J (U+004A): X=189.0,Y=-1.0 (should be at baseline 0?)

	* P (U+0050): X=317.0,Y=250.0 (should be at descender 251?)

	* P (U+0050): X=291.0,Y=250.0 (should be at descender 251?)

	* Y (U+0059): X=271.0,Y=253.0 (should be at descender 251?)

	* k (U+006B): X=322.0,Y=252.0 (should be at descender 251?)

	* sterling (U+00A3): X=117.5,Y=249.5 (should be at descender 251?)

	* ordfeminine (U+00AA): X=87.0,Y=688.0 (should be at cap-height 690?)

	* Yacute (U+00DD): X=271.0,Y=253.0 (should be at descender 251?)

	* germandbls (U+00DF): X=395.0,Y=-0.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=621.0,Y=936.0 (should be at ascender 935?)

	* Ccaron (U+010C): X=215.0,Y=936.0 (should be at ascender 935?)

	* Dcaron (U+010E): X=576.0,Y=936.0 (should be at ascender 935?)

	* Dcaron (U+010E): X=170.0,Y=936.0 (should be at ascender 935?)

	* Ecaron (U+011A): X=523.0,Y=936.0 (should be at ascender 935?)

	* Ecaron (U+011A): X=117.0,Y=936.0 (should be at ascender 935?)

	* Gcircumflex (U+011C): X=496.5,Y=1.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=496.5,Y=1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=496.5,Y=1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=496.5,Y=1.0 (should be at baseline 0?)

	* iogonek (U+012F): X=153.0,Y=-2.0 (should be at baseline 0?)

	* IJ (U+0132): X=555.0,Y=-1.0 (should be at baseline 0?)

	* Jcircumflex (U+0134): X=189.0,Y=-1.0 (should be at baseline 0?)

	* uni0137 (U+0137): X=322.0,Y=252.0 (should be at descender 251?)

	* Ncaron (U+0147): X=586.0,Y=936.0 (should be at ascender 935?)

	* Ncaron (U+0147): X=180.0,Y=936.0 (should be at ascender 935?)

	* Ohungarumlaut (U+0150): X=496.0,Y=936.0 (should be at ascender 935?)

	* Rcaron (U+0158): X=553.0,Y=936.0 (should be at ascender 935?)

	* Rcaron (U+0158): X=147.0,Y=936.0 (should be at ascender 935?)

	* Scaron (U+0160): X=519.0,Y=936.0 (should be at ascender 935?)

	* Scaron (U+0160): X=113.0,Y=936.0 (should be at ascender 935?)

	* Tcaron (U+0164): X=578.0,Y=936.0 (should be at ascender 935?)

	* Tcaron (U+0164): X=172.0,Y=936.0 (should be at ascender 935?)

	* Uhungarumlaut (U+0170): X=487.0,Y=936.0 (should be at ascender 935?)

	* Ycircumflex (U+0176): X=271.0,Y=253.0 (should be at descender 251?)

	* Ydieresis (U+0178): X=271.0,Y=253.0 (should be at descender 251?)

	* Zcaron (U+017D): X=539.0,Y=936.0 (should be at ascender 935?)

	* Zcaron (U+017D): X=133.0,Y=936.0 (should be at ascender 935?)

	* uni01CD (U+01CD): X=570.0,Y=936.0 (should be at ascender 935?)

	* uni01CD (U+01CD): X=164.0,Y=936.0 (should be at ascender 935?)

	* Gcaron (U+01E6): X=496.5,Y=1.0 (should be at baseline 0?)

	* Gcaron (U+01E6): X=623.0,Y=936.0 (should be at ascender 935?)

	* Gcaron (U+01E6): X=217.0,Y=936.0 (should be at ascender 935?)

	* uni0232 (U+0232): X=271.0,Y=253.0 (should be at descender 251?)

	* uni0259 (U+0259): X=34.0,Y=252.0 (should be at descender 251?)

	* uni0259 (U+0259): X=358.0,Y=252.0 (should be at descender 251?)

	* uni0E3F (U+0E3F): X=399.0,Y=2.0 (should be at baseline 0?)

	* uni1E20 (U+1E20): X=496.5,Y=1.0 (should be at baseline 0?)

	* uni1EA4 (U+1EA4): X=338.0,Y=936.0 (should be at ascender 935?)

	* uni1EA4 (U+1EA4): X=396.0,Y=936.0 (should be at ascender 935?)

	* uni1EA6 (U+1EA6): X=338.0,Y=936.0 (should be at ascender 935?)

	* uni1EA6 (U+1EA6): X=396.0,Y=936.0 (should be at ascender 935?)

	* uni1EA8 (U+1EA8): X=338.0,Y=936.0 (should be at ascender 935?)

	* uni1EA8 (U+1EA8): X=396.0,Y=936.0 (should be at ascender 935?)

	* uni1EAA (U+1EAA): X=338.0,Y=936.0 (should be at ascender 935?)

	* uni1EAA (U+1EAA): X=396.0,Y=936.0 (should be at ascender 935?)

	* uni1EAB (U+1EAB): X=488.0,Y=934.0 (should be at ascender 935?)

	* uni1EAF (U+1EAF): X=213.5,Y=692.0 (should be at cap-height 690?)

	* uni1EAF (U+1EAF): X=398.5,Y=692.0 (should be at cap-height 690?)

	* uni1EB1 (U+1EB1): X=218.5,Y=692.0 (should be at cap-height 690?)

	* uni1EB1 (U+1EB1): X=403.5,Y=692.0 (should be at cap-height 690?)

	* uni1EB3 (U+1EB3): X=213.5,Y=692.0 (should be at cap-height 690?)

	* uni1EB3 (U+1EB3): X=398.5,Y=692.0 (should be at cap-height 690?)

	* uni1EB4 (U+1EB4): X=392.5,Y=936.0 (should be at ascender 935?)

	* uni1EB5 (U+1EB5): X=213.5,Y=692.0 (should be at cap-height 690?)

	* uni1EB5 (U+1EB5): X=398.5,Y=692.0 (should be at cap-height 690?)

	* uni1EBE (U+1EBE): X=291.0,Y=936.0 (should be at ascender 935?)

	* uni1EBE (U+1EBE): X=349.0,Y=936.0 (should be at ascender 935?)

	* uni1EC0 (U+1EC0): X=291.0,Y=936.0 (should be at ascender 935?)

	* uni1EC0 (U+1EC0): X=349.0,Y=936.0 (should be at ascender 935?)

	* uni1EC2 (U+1EC2): X=291.0,Y=936.0 (should be at ascender 935?)

	* uni1EC2 (U+1EC2): X=349.0,Y=936.0 (should be at ascender 935?)

	* uni1EC4 (U+1EC4): X=291.0,Y=936.0 (should be at ascender 935?)

	* uni1EC4 (U+1EC4): X=349.0,Y=936.0 (should be at ascender 935?)

	* uni1EC5 (U+1EC5): X=490.0,Y=934.0 (should be at ascender 935?)

	* uni1ED0 (U+1ED0): X=391.0,Y=936.0 (should be at ascender 935?)

	* uni1ED0 (U+1ED0): X=449.0,Y=936.0 (should be at ascender 935?)

	* uni1ED2 (U+1ED2): X=391.0,Y=936.0 (should be at ascender 935?)

	* uni1ED2 (U+1ED2): X=449.0,Y=936.0 (should be at ascender 935?)

	* uni1ED4 (U+1ED4): X=391.0,Y=936.0 (should be at ascender 935?)

	* uni1ED4 (U+1ED4): X=449.0,Y=936.0 (should be at ascender 935?)

	* uni1ED6 (U+1ED6): X=391.0,Y=936.0 (should be at ascender 935?)

	* uni1ED6 (U+1ED6): X=449.0,Y=936.0 (should be at ascender 935?)

	* uni1ED7 (U+1ED7): X=512.0,Y=934.0 (should be at ascender 935?)

	* Ygrave (U+1EF2): X=271.0,Y=253.0 (should be at descender 251?)

	* uni1EF4 (U+1EF4): X=271.0,Y=253.0 (should be at descender 251?)

	* uni1EF6 (U+1EF6): X=271.0,Y=253.0 (should be at descender 251?)

	* uni1EF8 (U+1EF8): X=271.0,Y=253.0 (should be at descender 251?)

	* dong (U+20AB): X=540.0,Y=249.0 (should be at descender 251?)

	* uni20BF (U+20BF): X=367.0,Y=1.0 (should be at baseline 0?) 

	* infinity (U+221E): X=645.0,Y=252.0 (should be at descender 251?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Z (U+005A): L<<44.0,706.0>--<64.0,706.0>> -> L<<64.0,706.0>--<231.0,690.0>>

	* Z (U+005A): L<<64.0,706.0>--<231.0,690.0>> -> L<<231.0,690.0>--<640.0,690.0>>

	* Zacute (U+0179): L<<44.0,706.0>--<64.0,706.0>> -> L<<64.0,706.0>--<231.0,690.0>>

	* Zacute (U+0179): L<<64.0,706.0>--<231.0,690.0>> -> L<<231.0,690.0>--<640.0,690.0>>

	* Zcaron (U+017D): L<<44.0,706.0>--<64.0,706.0>> -> L<<64.0,706.0>--<231.0,690.0>>

	* Zcaron (U+017D): L<<64.0,706.0>--<231.0,690.0>> -> L<<231.0,690.0>--<640.0,690.0>>

	* Zdotaccent (U+017B): L<<44.0,706.0>--<64.0,706.0>> -> L<<64.0,706.0>--<231.0,690.0>>

	* Zdotaccent (U+017B): L<<64.0,706.0>--<231.0,690.0>> -> L<<231.0,690.0>--<640.0,690.0>>

	* fi (U+FB01): L<<281.0,480.0>--<649.0,513.0>> -> L<<649.0,513.0>--<682.0,513.0>>

	* trademark (U+2122): L<<12.0,696.0>--<73.0,690.0>> -> L<<73.0,690.0>--<207.0,690.0>>

	* trademark (U+2122): L<<2.0,696.0>--<12.0,696.0>> -> L<<12.0,696.0>--<73.0,690.0>>

	* trademark (U+2122): L<<207.0,690.0>--<268.0,696.0>> -> L<<268.0,696.0>--<278.0,696.0>>

	* trademark (U+2122): L<<73.0,690.0>--<207.0,690.0>> -> L<<207.0,690.0>--<268.0,696.0>> 

	* uni00B5 (U+00B5): L<<79.0,156.0>--<79.0,157.0>> -> L<<79.0,157.0>--<79.0,350.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni1EA7 (U+1EA7): L<<510.0,940.0>--<509.0,686.0>>

	* uni1EC1 (U+1EC1): L<<512.0,940.0>--<511.0,686.0>> 

	* uni1ED3 (U+1ED3): L<<534.0,940.0>--<533.0,686.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[21] Platypi-RegularItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Version format is correct in 'name' table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/version_format">com.google.fonts/check/name/version_format</a>)</summary><div>


* 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000. Current version string is: "Version 0.350; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.33]" [code: bad-version-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Platypi Italic | Platypi |
| Subfamily Name | Regular | Italic |
| Full Name | Platypi Regular Italic | Platypi Italic |
| Poscript Name | Platypi-RegularItalic | Platypi-Italic |
| Typographic Family Name | Platypi | N/A |
| Typographic Subfamily Name | Regular Italic | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Platypi-SemiBoldItalic.ttf', 'fonts/ttf/Platypi-ExtraBoldItalic.ttf', 'fonts/ttf/Platypi-LightItalic.ttf', 'fonts/ttf/Platypi-RegularItalic.ttf', 'fonts/ttf/Platypi-BoldItalic.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1123, but got 965 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 342, but got 235 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (765) and hhea ascent (965) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Does full font name begin with the font family name? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/name/match_familyname_fullfont">com.google.fonts/check/name/match_familyname_fullfont</a>)</summary><div>


* 🔥 **FAIL** On the 'name' table, the full font name 'Platypi Regular Italic' does not begin with the font family name 'Platypi Italic' in platformID 3, encodingID 1, languageID 1033(0409), and nameID 1. [code: mismatch-font-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'BOLT' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.TRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

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

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=321.0,Y=692.0 (should be at cap-height 690?)

	* parenleft (U+0028): X=58.5,Y=1.5 (should be at baseline 0?)

	* question (U+003F): X=232.5,Y=691.0 (should be at cap-height 690?)

	* at (U+0040): X=475.0,Y=689.0 (should be at cap-height 690?)

	* at (U+0040): X=102.5,Y=1.0 (should be at baseline 0?)

	* at (U+0040): X=811.0,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=564.5,Y=689.0 (should be at cap-height 690?)

	* bracketleft (U+005B): X=269.0,Y=688.0 (should be at cap-height 690?)

	* bracketright (U+005D): X=228.0,Y=688.0 (should be at cap-height 690?)

	* g (U+0067): X=495.0,Y=482.0 (should be at x-height 484?)

	* section (U+00A7): X=280.5,Y=689.0 (should be at cap-height 690?)

	* registered (U+00AE): X=280.0,Y=688.0 (should be at cap-height 690?)

	* registered (U+00AE): X=393.0,Y=688.0 (should be at cap-height 690?)

	* uni00B5 (U+00B5): X=-25.0,Y=-237.0 (should be at descender -235?)

	* uni00B5 (U+00B5): X=-31.0,Y=-237.0 (should be at descender -235?)

	* cedilla (U+00B8): X=110.0,Y=-234.0 (should be at descender -235?)

	* Ccedilla (U+00C7): X=287.0,Y=-234.0 (should be at descender -235?)

	* ccedilla (U+00E7): X=203.0,Y=-234.0 (should be at descender -235?)

	* Abreve (U+0102): X=328.5,Y=767.0 (should be at ascender 765?)

	* Aogonek (U+0104): X=488.0,Y=-2.0 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=411.5,Y=763.0 (should be at ascender 765?)

	* ccaron (U+010D): X=232.0,Y=767.0 (should be at ascender 765?)

	* dcaron (U+010F): X=643.0,Y=767.0 (should be at ascender 765?)

	* dcaron (U+010F): X=646.0,Y=767.0 (should be at ascender 765?)

	* Ebreve (U+0114): X=340.5,Y=767.0 (should be at ascender 765?)

	* Edotaccent (U+0116): X=373.5,Y=763.0 (should be at ascender 765?)

	* Eogonek (U+0118): X=364.0,Y=-2.0 (should be at baseline 0?)

	* ecaron (U+011B): X=229.0,Y=767.0 (should be at ascender 765?)

	* Gcircumflex (U+011C): X=564.5,Y=689.0 (should be at cap-height 690?)

	* Gbreve (U+011E): X=564.5,Y=689.0 (should be at cap-height 690?)

	* Gbreve (U+011E): X=389.5,Y=767.0 (should be at ascender 765?)

	* Gdotaccent (U+0120): X=564.5,Y=689.0 (should be at cap-height 690?)

	* Gdotaccent (U+0120): X=422.5,Y=763.0 (should be at ascender 765?)

	* uni0122 (U+0122): X=564.5,Y=689.0 (should be at cap-height 690?)

	* Ibreve (U+012C): X=193.5,Y=767.0 (should be at ascender 765?)

	* Iogonek (U+012E): X=83.0,Y=-2.0 (should be at baseline 0?)

	* Idotaccent (U+0130): X=226.5,Y=763.0 (should be at ascender 765?)

	* Lcaron (U+013D): X=444.0,Y=692.0 (should be at cap-height 690?)

	* Lcaron (U+013D): X=447.0,Y=692.0 (should be at cap-height 690?)

	* lcaron (U+013E): X=358.0,Y=767.0 (should be at ascender 765?)

	* lcaron (U+013E): X=361.0,Y=767.0 (should be at ascender 765?)

	* ncaron (U+0148): X=291.0,Y=767.0 (should be at ascender 765?)

	* Obreve (U+014E): X=401.5,Y=767.0 (should be at ascender 765?)

	* rcaron (U+0159): X=208.0,Y=767.0 (should be at ascender 765?)

	* Scedilla (U+015E): X=268.0,Y=-234.0 (should be at descender -235?)

	* scedilla (U+015F): X=198.0,Y=-234.0 (should be at descender -235?)

	* scaron (U+0161): X=198.0,Y=767.0 (should be at ascender 765?)

	* tcaron (U+0165): X=355.0,Y=767.0 (should be at ascender 765?)

	* tcaron (U+0165): X=358.0,Y=767.0 (should be at ascender 765?)

	* Ubreve (U+016C): X=402.5,Y=767.0 (should be at ascender 765?)

	* Uogonek (U+0172): X=312.0,Y=-2.0 (should be at baseline 0?)

	* Zdotaccent (U+017B): X=353.5,Y=763.0 (should be at ascender 765?)

	* zcaron (U+017E): X=224.0,Y=767.0 (should be at ascender 765?)

	* uni018F (U+018F): X=235.5,Y=691.5 (should be at cap-height 690?)

	* uni01CE (U+01CE): X=264.0,Y=767.0 (should be at ascender 765?)

	* Gcaron (U+01E6): X=564.5,Y=689.0 (should be at cap-height 690?)

	* gcaron (U+01E7): X=212.0,Y=767.0 (should be at ascender 765?)

	* caron (U+02C7): X=161.0,Y=767.0 (should be at ascender 765?)

	* uni030C (U+030C): X=161.0,Y=767.0 (should be at ascender 765?)

	* uni0327 (U+0327): X=110.0,Y=-234.0 (should be at descender -235?)

	* uni1EA2 (U+1EA2): X=332.0,Y=764.0 (should be at ascender 765?)

	* uni1EAB (U+1EAB): X=453.0,Y=767.0 (should be at ascender 765?)

	* uni1EB3 (U+1EB3): X=357.0,Y=692.0 (should be at cap-height 690?)

	* uni1EB6 (U+1EB6): X=330.5,Y=767.0 (should be at ascender 765?)

	* uni1EBA (U+1EBA): X=344.0,Y=764.0 (should be at ascender 765?)

	* uni1EC5 (U+1EC5): X=418.0,Y=767.0 (should be at ascender 765?)

	* uni1EC8 (U+1EC8): X=197.0,Y=764.0 (should be at ascender 765?)

	* uni1ECE (U+1ECE): X=405.0,Y=764.0 (should be at ascender 765?)

	* uni1ED7 (U+1ED7): X=434.0,Y=767.0 (should be at ascender 765?)

	* uni1EDE (U+1EDE): X=405.0,Y=764.0 (should be at ascender 765?)

	* uni1EE0 (U+1EE0): X=267.0,Y=763.0 (should be at ascender 765?)

	* uni1EE6 (U+1EE6): X=406.0,Y=764.0 (should be at ascender 765?)

	* uni1EEC (U+1EEC): X=406.0,Y=764.0 (should be at ascender 765?)

	* uni1EEE (U+1EEE): X=302.0,Y=763.0 (should be at ascender 765?)

	* uni1EF6 (U+1EF6): X=375.0,Y=764.0 (should be at ascender 765?)

	* quoteright (U+2019): X=279.5,Y=688.0 (should be at cap-height 690?)

	* quotedblright (U+201D): X=458.5,Y=688.0 (should be at cap-height 690?) 

	* quotedblright (U+201D): X=279.5,Y=688.0 (should be at cap-height 690?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<271.0,690.0>--<706.0,690.0>> -> L<<706.0,690.0>--<827.0,698.0>>

	* AE (U+00C6): L<<706.0,690.0>--<827.0,698.0>> -> L<<827.0,698.0>--<839.0,698.0>>

	* AEacute (U+01FC): L<<271.0,690.0>--<706.0,690.0>> -> L<<706.0,690.0>--<827.0,698.0>>

	* AEacute (U+01FC): L<<706.0,690.0>--<827.0,698.0>> -> L<<827.0,698.0>--<839.0,698.0>>

	* B (U+0042): L<<248.0,392.0>--<285.0,392.0>> -> L<<285.0,392.0>--<385.0,394.0>>

	* E (U+0045): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* E (U+0045): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* Eacute (U+00C9): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* Eacute (U+00C9): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* Ebreve (U+0114): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* Ebreve (U+0114): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* Ecaron (U+011A): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* Ecaron (U+011A): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* Ecircumflex (U+00CA): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* Ecircumflex (U+00CA): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* Edieresis (U+00CB): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* Edieresis (U+00CB): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* Edotaccent (U+0116): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* Edotaccent (U+0116): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* Egrave (U+00C8): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* Egrave (U+00C8): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* Emacron (U+0112): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* Emacron (U+0112): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* Eogonek (U+0118): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* Eogonek (U+0118): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* F (U+0046): L<<125.0,690.0>--<479.0,690.0>> -> L<<479.0,690.0>--<600.0,698.0>>

	* F (U+0046): L<<479.0,690.0>--<600.0,698.0>> -> L<<600.0,698.0>--<613.0,698.0>>

	* K (U+004B): L<<762.0,673.0>--<638.0,597.0>> -> L<<638.0,597.0>--<412.0,436.0>>

	* OE (U+0152): L<<514.0,690.0>--<855.0,690.0>> -> L<<855.0,690.0>--<976.0,698.0>>

	* OE (U+0152): L<<855.0,690.0>--<976.0,698.0>> -> L<<976.0,698.0>--<989.0,698.0>>

	* T (U+0054): L<<138.0,698.0>--<150.0,698.0>> -> L<<150.0,698.0>--<270.0,690.0>>

	* T (U+0054): L<<150.0,698.0>--<270.0,690.0>> -> L<<270.0,690.0>--<583.0,690.0>>

	* T (U+0054): L<<270.0,690.0>--<583.0,690.0>> -> L<<583.0,690.0>--<714.0,698.0>>

	* T (U+0054): L<<583.0,690.0>--<714.0,698.0>> -> L<<714.0,698.0>--<727.0,698.0>>

	* Tcaron (U+0164): L<<138.0,698.0>--<150.0,698.0>> -> L<<150.0,698.0>--<270.0,690.0>>

	* Tcaron (U+0164): L<<150.0,698.0>--<270.0,690.0>> -> L<<270.0,690.0>--<583.0,690.0>>

	* Tcaron (U+0164): L<<270.0,690.0>--<583.0,690.0>> -> L<<583.0,690.0>--<714.0,698.0>>

	* Tcaron (U+0164): L<<583.0,690.0>--<714.0,698.0>> -> L<<714.0,698.0>--<727.0,698.0>>

	* Tmacronbelow (U+1E6E): L<<138.0,698.0>--<150.0,698.0>> -> L<<150.0,698.0>--<270.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<150.0,698.0>--<270.0,690.0>> -> L<<270.0,690.0>--<583.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<270.0,690.0>--<583.0,690.0>> -> L<<583.0,690.0>--<714.0,698.0>>

	* Tmacronbelow (U+1E6E): L<<583.0,690.0>--<714.0,698.0>> -> L<<714.0,698.0>--<727.0,698.0>>

	* Z (U+005A): L<<138.0,699.0>--<151.0,699.0>> -> L<<151.0,699.0>--<272.0,690.0>>

	* Z (U+005A): L<<151.0,699.0>--<272.0,690.0>> -> L<<272.0,690.0>--<631.0,690.0>>

	* Zacute (U+0179): L<<138.0,699.0>--<151.0,699.0>> -> L<<151.0,699.0>--<272.0,690.0>>

	* Zacute (U+0179): L<<151.0,699.0>--<272.0,690.0>> -> L<<272.0,690.0>--<631.0,690.0>>

	* Zcaron (U+017D): L<<138.0,699.0>--<151.0,699.0>> -> L<<151.0,699.0>--<272.0,690.0>>

	* Zcaron (U+017D): L<<151.0,699.0>--<272.0,690.0>> -> L<<272.0,690.0>--<631.0,690.0>>

	* Zdotaccent (U+017B): L<<138.0,699.0>--<151.0,699.0>> -> L<<151.0,699.0>--<272.0,690.0>>

	* Zdotaccent (U+017B): L<<151.0,699.0>--<272.0,690.0>> -> L<<272.0,690.0>--<631.0,690.0>>

	* trademark (U+2122): L<<145.0,695.0>--<153.0,695.0>> -> L<<153.0,695.0>--<212.0,690.0>>

	* trademark (U+2122): L<<153.0,695.0>--<212.0,690.0>> -> L<<212.0,690.0>--<342.0,690.0>>

	* trademark (U+2122): L<<212.0,690.0>--<342.0,690.0>> -> L<<342.0,690.0>--<402.0,695.0>>

	* trademark (U+2122): L<<342.0,690.0>--<402.0,695.0>> -> L<<402.0,695.0>--<411.0,695.0>>

	* uni00B5 (U+00B5): L<<-31.0,-237.0>--<83.0,162.0>> -> L<<83.0,162.0>--<84.0,167.0>>

	* uni00B5 (U+00B5): L<<83.0,162.0>--<84.0,167.0>> -> L<<84.0,167.0>--<138.0,356.0>>

	* uni0136 (U+0136): L<<762.0,673.0>--<638.0,597.0>> -> L<<638.0,597.0>--<412.0,436.0>>

	* uni021A (U+021A): L<<138.0,698.0>--<150.0,698.0>> -> L<<150.0,698.0>--<270.0,690.0>>

	* uni021A (U+021A): L<<150.0,698.0>--<270.0,690.0>> -> L<<270.0,690.0>--<583.0,690.0>>

	* uni021A (U+021A): L<<270.0,690.0>--<583.0,690.0>> -> L<<583.0,690.0>--<714.0,698.0>>

	* uni021A (U+021A): L<<583.0,690.0>--<714.0,698.0>> -> L<<714.0,698.0>--<727.0,698.0>>

	* uni1EB8 (U+1EB8): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* uni1EB8 (U+1EB8): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* uni1EBA (U+1EBA): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* uni1EBA (U+1EBA): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* uni1EBC (U+1EBC): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* uni1EBC (U+1EBC): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* uni1EBE (U+1EBE): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* uni1EBE (U+1EBE): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* uni1EC0 (U+1EC0): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* uni1EC0 (U+1EC0): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* uni1EC2 (U+1EC2): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* uni1EC2 (U+1EC2): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* uni1EC4 (U+1EC4): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>>

	* uni1EC4 (U+1EC4): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>>

	* uni1EC6 (U+1EC6): L<<125.0,690.0>--<496.0,690.0>> -> L<<496.0,690.0>--<617.0,698.0>> 

	* uni1EC6 (U+1EC6): L<<496.0,690.0>--<617.0,698.0>> -> L<<617.0,698.0>--<629.0,698.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[22] Platypi-BoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Version format is correct in 'name' table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/version_format">com.google.fonts/check/name/version_format</a>)</summary><div>


* 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000. Current version string is: "Version 0.350; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.33]" [code: bad-version-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Platypi Bold Italic | Platypi |
| Subfamily Name | Regular | Bold Italic |
| Full Name | Platypi Bold Italic | Platypi Bold Italic |
| Poscript Name | Platypi-BoldItalic | Platypi-BoldItalic |
| Typographic Family Name | Platypi | N/A |
| Typographic Subfamily Name | Bold Italic | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Platypi-SemiBoldItalic.ttf', 'fonts/ttf/Platypi-ExtraBoldItalic.ttf', 'fonts/ttf/Platypi-LightItalic.ttf', 'fonts/ttf/Platypi-RegularItalic.ttf', 'fonts/ttf/Platypi-BoldItalic.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1123, but got 965 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 342, but got 235 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (765) and hhea ascent (965) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle ITALIC bit should be set. [code: bad-ITALIC]
* 🔥 **FAIL** head macStyle BOLD bit should be set. [code: bad-BOLD]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be unset. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection ITALIC bit should be set. [code: bad-ITALIC]
* 🔥 **FAIL** OS/2 fsSelection BOLD bit should be set. [code: bad-BOLD]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table IDs 1, 2, 16, 17 to conform to Italic style. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/name/italic_names">com.google.fonts/check/name/italic_names</a>)</summary><div>


* 🔥 **FAIL** Name ID 1 (Family Name) must not contain 'Italic'. [code: bad-familyname]
* 🔥 **FAIL** Name ID 2 (Subfamily Name) does not conform to specs. Only R/I/B/BI are allowed.
Got: 'Regular'. [code: bad-subfamilyname]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'BOLT' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.TRK
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

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

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<291.0,690.0>--<738.0,690.0>> -> L<<738.0,690.0>--<882.0,698.0>>

	* AE (U+00C6): L<<738.0,690.0>--<882.0,698.0>> -> L<<882.0,698.0>--<899.0,698.0>>

	* AEacute (U+01FC): L<<291.0,690.0>--<738.0,690.0>> -> L<<738.0,690.0>--<882.0,698.0>>

	* AEacute (U+01FC): L<<738.0,690.0>--<882.0,698.0>> -> L<<882.0,698.0>--<899.0,698.0>>

	* E (U+0045): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* E (U+0045): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* Eacute (U+00C9): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* Eacute (U+00C9): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* Ebreve (U+0114): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* Ebreve (U+0114): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* Ecaron (U+011A): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* Ecaron (U+011A): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* Ecircumflex (U+00CA): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* Ecircumflex (U+00CA): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* Edieresis (U+00CB): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* Edieresis (U+00CB): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* Edotaccent (U+0116): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* Edotaccent (U+0116): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* Egrave (U+00C8): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* Egrave (U+00C8): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* Emacron (U+0112): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* Emacron (U+0112): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* Eogonek (U+0118): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* Eogonek (U+0118): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* F (U+0046): L<<121.0,690.0>--<481.0,690.0>> -> L<<481.0,690.0>--<624.0,698.0>>

	* F (U+0046): L<<481.0,690.0>--<624.0,698.0>> -> L<<624.0,698.0>--<641.0,698.0>>

	* K (U+004B): L<<834.0,669.0>--<701.0,593.0>> -> L<<701.0,593.0>--<481.0,442.0>>

	* OE (U+0152): L<<517.0,690.0>--<876.0,690.0>> -> L<<876.0,690.0>--<1020.0,698.0>>

	* OE (U+0152): L<<876.0,690.0>--<1020.0,698.0>> -> L<<1020.0,698.0>--<1037.0,698.0>>

	* T (U+0054): L<<131.0,698.0>--<149.0,698.0>> -> L<<149.0,698.0>--<284.0,690.0>>

	* T (U+0054): L<<149.0,698.0>--<284.0,690.0>> -> L<<284.0,690.0>--<589.0,690.0>>

	* T (U+0054): L<<284.0,690.0>--<589.0,690.0>> -> L<<589.0,690.0>--<748.0,698.0>>

	* T (U+0054): L<<589.0,690.0>--<748.0,698.0>> -> L<<748.0,698.0>--<766.0,698.0>>

	* Tcaron (U+0164): L<<131.0,698.0>--<149.0,698.0>> -> L<<149.0,698.0>--<284.0,690.0>>

	* Tcaron (U+0164): L<<149.0,698.0>--<284.0,690.0>> -> L<<284.0,690.0>--<589.0,690.0>>

	* Tcaron (U+0164): L<<284.0,690.0>--<589.0,690.0>> -> L<<589.0,690.0>--<748.0,698.0>>

	* Tcaron (U+0164): L<<589.0,690.0>--<748.0,698.0>> -> L<<748.0,698.0>--<766.0,698.0>>

	* Tmacronbelow (U+1E6E): L<<131.0,698.0>--<149.0,698.0>> -> L<<149.0,698.0>--<284.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<149.0,698.0>--<284.0,690.0>> -> L<<284.0,690.0>--<589.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<284.0,690.0>--<589.0,690.0>> -> L<<589.0,690.0>--<748.0,698.0>>

	* Tmacronbelow (U+1E6E): L<<589.0,690.0>--<748.0,698.0>> -> L<<748.0,698.0>--<766.0,698.0>>

	* Z (U+005A): L<<133.0,704.0>--<151.0,704.0>> -> L<<151.0,704.0>--<307.0,690.0>>

	* Z (U+005A): L<<151.0,704.0>--<307.0,690.0>> -> L<<307.0,690.0>--<673.0,690.0>>

	* Zacute (U+0179): L<<133.0,704.0>--<151.0,704.0>> -> L<<151.0,704.0>--<307.0,690.0>>

	* Zacute (U+0179): L<<151.0,704.0>--<307.0,690.0>> -> L<<307.0,690.0>--<673.0,690.0>>

	* Zcaron (U+017D): L<<133.0,704.0>--<151.0,704.0>> -> L<<151.0,704.0>--<307.0,690.0>>

	* Zcaron (U+017D): L<<151.0,704.0>--<307.0,690.0>> -> L<<307.0,690.0>--<673.0,690.0>>

	* Zdotaccent (U+017B): L<<133.0,704.0>--<151.0,704.0>> -> L<<151.0,704.0>--<307.0,690.0>>

	* Zdotaccent (U+017B): L<<151.0,704.0>--<307.0,690.0>> -> L<<307.0,690.0>--<673.0,690.0>>

	* three (U+0033): L<<306.0,328.0>--<316.0,365.0>> -> L<<316.0,365.0>--<324.0,396.0>>

	* trademark (U+2122): L<<138.0,696.0>--<147.0,696.0>> -> L<<147.0,696.0>--<207.0,690.0>>

	* trademark (U+2122): L<<147.0,696.0>--<207.0,690.0>> -> L<<207.0,690.0>--<340.0,690.0>>

	* trademark (U+2122): L<<207.0,690.0>--<340.0,690.0>> -> L<<340.0,690.0>--<401.0,696.0>>

	* trademark (U+2122): L<<340.0,690.0>--<401.0,696.0>> -> L<<401.0,696.0>--<411.0,696.0>>

	* uni00B5 (U+00B5): L<<-52.0,-236.0>--<66.0,176.0>> -> L<<66.0,176.0>--<67.0,179.0>>

	* uni00B5 (U+00B5): L<<66.0,176.0>--<67.0,179.0>> -> L<<67.0,179.0>--<121.0,366.0>>

	* uni0136 (U+0136): L<<834.0,669.0>--<701.0,593.0>> -> L<<701.0,593.0>--<481.0,442.0>>

	* uni021A (U+021A): L<<131.0,698.0>--<149.0,698.0>> -> L<<149.0,698.0>--<284.0,690.0>>

	* uni021A (U+021A): L<<149.0,698.0>--<284.0,690.0>> -> L<<284.0,690.0>--<589.0,690.0>>

	* uni021A (U+021A): L<<284.0,690.0>--<589.0,690.0>> -> L<<589.0,690.0>--<748.0,698.0>>

	* uni021A (U+021A): L<<589.0,690.0>--<748.0,698.0>> -> L<<748.0,698.0>--<766.0,698.0>>

	* uni1EB8 (U+1EB8): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* uni1EB8 (U+1EB8): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* uni1EBA (U+1EBA): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* uni1EBA (U+1EBA): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* uni1EBC (U+1EBC): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* uni1EBC (U+1EBC): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* uni1EBE (U+1EBE): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* uni1EBE (U+1EBE): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* uni1EC0 (U+1EC0): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* uni1EC0 (U+1EC0): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* uni1EC2 (U+1EC2): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* uni1EC2 (U+1EC2): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* uni1EC4 (U+1EC4): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>>

	* uni1EC4 (U+1EC4): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>>

	* uni1EC6 (U+1EC6): L<<121.0,690.0>--<489.0,690.0>> -> L<<489.0,690.0>--<632.0,698.0>> 

	* uni1EC6 (U+1EC6): L<<489.0,690.0>--<632.0,698.0>> -> L<<632.0,698.0>--<650.0,698.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[17] Platypi-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'Semi Bold'. Expected OS/2 usWeightClass is 700, got 600. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Version format is correct in 'name' table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/version_format">com.google.fonts/check/name/version_format</a>)</summary><div>


* 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000. Current version string is: "Version %d.%03d; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.33]" [code: bad-version-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Platypi Semi Bold | Platypi Semi |
| Subfamily Name | Regular | Bold |
| Full Name | Platypi Semi Bold | Platypi Semi Bold |
| Poscript Name | Platypi-SemiBold | PlatypiSemi-Bold |
| Typographic Family Name | Platypi | N/A |
| Typographic Subfamily Name | Semi Bold | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1186 when it should be at least 1200 [code: bad-hhea-range]
* 🔥 **FAIL** The OS/2 sTypoDescender must be negative or zero. This font has a strictly positive value. [code: typo-descender]
* 🔥 **FAIL** The hhea descender must be negative or zero. This font has a strictly positive value. [code: hhea-descent]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Platypi-SemiBoldItalic.ttf', 'fonts/ttf/Platypi-ExtraBoldItalic.ttf', 'fonts/ttf/Platypi-LightItalic.ttf', 'fonts/ttf/Platypi-RegularItalic.ttf', 'fonts/ttf/Platypi-BoldItalic.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ i̦̓ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ j̦̓ į̆ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** name version string for platform 3, encoding 1 ("Version %d.%03d; ttfautohint (v1.8.4.7-5d5b);gftools[0.9.33]"), could not be parsed. [code: parse]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'BOLT' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<288.0,690.0>--<748.0,690.0>> -> L<<748.0,690.0>--<883.0,702.0>>

	* AE (U+00C6): L<<748.0,690.0>--<883.0,702.0>> -> L<<883.0,702.0>--<898.0,702.0>>

	* AEacute (U+01FC): L<<288.0,690.0>--<748.0,690.0>> -> L<<748.0,690.0>--<883.0,702.0>>

	* AEacute (U+01FC): L<<748.0,690.0>--<883.0,702.0>> -> L<<883.0,702.0>--<898.0,702.0>>

	* E (U+0045): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* E (U+0045): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* Eacute (U+00C9): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* Eacute (U+00C9): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* Ebreve (U+0114): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* Ebreve (U+0114): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* Ecaron (U+011A): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* Ecaron (U+011A): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* Ecircumflex (U+00CA): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* Ecircumflex (U+00CA): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* Edieresis (U+00CB): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* Edieresis (U+00CB): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* Edotaccent (U+0116): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* Edotaccent (U+0116): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* Egrave (U+00C8): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* Egrave (U+00C8): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* Emacron (U+0112): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* Emacron (U+0112): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* Eogonek (U+0118): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* Eogonek (U+0118): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* F (U+0046): L<<28.0,690.0>--<409.0,690.0>> -> L<<409.0,690.0>--<544.0,702.0>>

	* F (U+0046): L<<409.0,690.0>--<544.0,702.0>> -> L<<544.0,702.0>--<560.0,702.0>>

	* OE (U+0152): L<<432.0,690.0>--<806.0,690.0>> -> L<<806.0,690.0>--<941.0,702.0>>

	* OE (U+0152): L<<806.0,690.0>--<941.0,702.0>> -> L<<941.0,702.0>--<956.0,702.0>>

	* T (U+0054): L<<197.0,690.0>--<522.0,690.0>> -> L<<522.0,690.0>--<659.0,702.0>>

	* T (U+0054): L<<42.0,702.0>--<60.0,702.0>> -> L<<60.0,702.0>--<197.0,690.0>>

	* T (U+0054): L<<522.0,690.0>--<659.0,702.0>> -> L<<659.0,702.0>--<677.0,702.0>>

	* T (U+0054): L<<60.0,702.0>--<197.0,690.0>> -> L<<197.0,690.0>--<522.0,690.0>>

	* Tbar (U+0166): L<<197.0,690.0>--<522.0,690.0>> -> L<<522.0,690.0>--<659.0,702.0>>

	* Tbar (U+0166): L<<42.0,702.0>--<60.0,702.0>> -> L<<60.0,702.0>--<197.0,690.0>>

	* Tbar (U+0166): L<<522.0,690.0>--<659.0,702.0>> -> L<<659.0,702.0>--<677.0,702.0>>

	* Tbar (U+0166): L<<60.0,702.0>--<197.0,690.0>> -> L<<197.0,690.0>--<522.0,690.0>>

	* Tcaron (U+0164): L<<197.0,690.0>--<522.0,690.0>> -> L<<522.0,690.0>--<659.0,702.0>>

	* Tcaron (U+0164): L<<42.0,702.0>--<60.0,702.0>> -> L<<60.0,702.0>--<197.0,690.0>>

	* Tcaron (U+0164): L<<522.0,690.0>--<659.0,702.0>> -> L<<659.0,702.0>--<677.0,702.0>>

	* Tcaron (U+0164): L<<60.0,702.0>--<197.0,690.0>> -> L<<197.0,690.0>--<522.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<197.0,690.0>--<522.0,690.0>> -> L<<522.0,690.0>--<659.0,702.0>>

	* Tmacronbelow (U+1E6E): L<<42.0,702.0>--<60.0,702.0>> -> L<<60.0,702.0>--<197.0,690.0>>

	* Tmacronbelow (U+1E6E): L<<522.0,690.0>--<659.0,702.0>> -> L<<659.0,702.0>--<677.0,702.0>>

	* Tmacronbelow (U+1E6E): L<<60.0,702.0>--<197.0,690.0>> -> L<<197.0,690.0>--<522.0,690.0>>

	* Z (U+005A): L<<50.0,702.0>--<68.0,702.0>> -> L<<68.0,702.0>--<222.0,690.0>>

	* Z (U+005A): L<<68.0,702.0>--<222.0,690.0>> -> L<<222.0,690.0>--<606.0,690.0>>

	* Zacute (U+0179): L<<50.0,702.0>--<68.0,702.0>> -> L<<68.0,702.0>--<222.0,690.0>>

	* Zacute (U+0179): L<<68.0,702.0>--<222.0,690.0>> -> L<<222.0,690.0>--<606.0,690.0>>

	* Zcaron (U+017D): L<<50.0,702.0>--<68.0,702.0>> -> L<<68.0,702.0>--<222.0,690.0>>

	* Zcaron (U+017D): L<<68.0,702.0>--<222.0,690.0>> -> L<<222.0,690.0>--<606.0,690.0>>

	* Zdotaccent (U+017B): L<<50.0,702.0>--<68.0,702.0>> -> L<<68.0,702.0>--<222.0,690.0>>

	* Zdotaccent (U+017B): L<<68.0,702.0>--<222.0,690.0>> -> L<<222.0,690.0>--<606.0,690.0>>

	* fi (U+FB01): L<<244.0,474.0>--<594.0,500.0>> -> L<<594.0,500.0>--<622.0,500.0>>

	* trademark (U+2122): L<<11.0,696.0>--<71.0,690.0>> -> L<<71.0,690.0>--<203.0,690.0>>

	* trademark (U+2122): L<<2.0,696.0>--<11.0,696.0>> -> L<<11.0,696.0>--<71.0,690.0>>

	* trademark (U+2122): L<<203.0,690.0>--<263.0,696.0>> -> L<<263.0,696.0>--<272.0,696.0>>

	* trademark (U+2122): L<<71.0,690.0>--<203.0,690.0>> -> L<<203.0,690.0>--<263.0,696.0>>

	* uni0162 (U+0162): L<<197.0,690.0>--<522.0,690.0>> -> L<<522.0,690.0>--<659.0,702.0>>

	* uni0162 (U+0162): L<<42.0,702.0>--<60.0,702.0>> -> L<<60.0,702.0>--<197.0,690.0>>

	* uni0162 (U+0162): L<<522.0,690.0>--<659.0,702.0>> -> L<<659.0,702.0>--<677.0,702.0>>

	* uni0162 (U+0162): L<<60.0,702.0>--<197.0,690.0>> -> L<<197.0,690.0>--<522.0,690.0>>

	* uni018F (U+018F): L<<39.0,331.0>--<526.0,331.0>> -> L<<526.0,331.0>--<526.0,331.0>>

	* uni021A (U+021A): L<<197.0,690.0>--<522.0,690.0>> -> L<<522.0,690.0>--<659.0,702.0>>

	* uni021A (U+021A): L<<42.0,702.0>--<60.0,702.0>> -> L<<60.0,702.0>--<197.0,690.0>>

	* uni021A (U+021A): L<<522.0,690.0>--<659.0,702.0>> -> L<<659.0,702.0>--<677.0,702.0>>

	* uni021A (U+021A): L<<60.0,702.0>--<197.0,690.0>> -> L<<197.0,690.0>--<522.0,690.0>>

	* uni0E3F (U+0E3F): L<<248.0,379.0>--<260.0,379.0>> -> L<<260.0,379.0>--<317.0,382.0>>

	* uni1EB8 (U+1EB8): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* uni1EB8 (U+1EB8): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* uni1EBA (U+1EBA): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* uni1EBA (U+1EBA): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* uni1EBC (U+1EBC): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* uni1EBC (U+1EBC): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* uni1EBE (U+1EBE): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* uni1EBE (U+1EBE): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* uni1EC0 (U+1EC0): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* uni1EC0 (U+1EC0): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* uni1EC2 (U+1EC2): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* uni1EC2 (U+1EC2): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* uni1EC4 (U+1EC4): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>>

	* uni1EC4 (U+1EC4): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>>

	* uni1EC6 (U+1EC6): L<<28.0,690.0>--<422.0,690.0>> -> L<<422.0,690.0>--<557.0,702.0>> 

	* uni1EC6 (U+1EC6): L<<422.0,690.0>--<557.0,702.0>> -> L<<557.0,702.0>--<572.0,702.0>> [code: found-colinear-vectors]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 110 | 89 | 1188 | 61 | 859 | 0 |
| 0% | 5% | 4% | 51% | 3% | 37% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**