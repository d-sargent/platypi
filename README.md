# Platypi

[![][Fontbakery]](https://d-sargent.github.io/platypi/fontbakery/fontbakery-report.html)
[![][Universal]](https://d-sargent.github.io/platypi/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://d-sargent.github.io/platypi/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://d-sargent.github.io/platypi/fontbakery/fontbakery-report.html)
[![][Shaping]](https://d-sargent.github.io/platypi/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fd-sargent%2Fplatypi%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fd-sargent%2Fplatypi%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fd-sargent%2Fplatypi%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fd-sargent%2Fplatypi%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fd-sargent%2Fplatypi%2Fgh-pages%2Fbadges%2FUniversal.json

Inspired by the enigmatic Australian platypus, _Platypi_ blends heavy wedge serifs usually seen in display faces with more conventional curves and proportions to achieve a practical text typeface with a unique and distinctive visual rhythm. Heavier weights push this tension further with increased stroke tapering and overall contrast. The name _Platypi_ is a word commonly used as the plural of platypus, allthough this term is technically incorrect.

_Platypi_ features six weights with matching italic styles and language support for Indigenous Australian and Vietnamese languages.

![Sample Image](documentation/platypi-sample-images-jan-2024-2.png)
![Sample Image](documentation/platypi-sample-images-jan-2024-3.png)
![Sample Image](documentation/platypi-sample-images-jan-2024-4.png)
![Sample Image](documentation/platypi-sample-images-jan-2024-5.png)

## About the Designer

David Sargent is an Australian academic and designer living and working on Jagera and Turrbal land. 

He is Creative Director of [Liveworm](https://liveworm.com.au), a work-integrated learning incubator within the [Queensland College of Art & Design](https://www.griffith.edu.au/arts-education-law/queensland-college-art-design), Griffith University. Liveworm operates as a working design studio for students to engage with a broad range of ‘real world’ projects for not-for-profit, cultural, educational, and small to medium commercial clients. 

As a design researcher, David is interested in how creative practice can engage, communicate, and spark social change. His studio practice focuses on typography, expressive lettering, and disruptive augmented reality, with creative works exhibited in Australian and international galleries. He releases typefaces under the moniker Bolt Cutter Type.

## Contributors

The original design was developed while studying at _Type West_ under the guidance of:

* Juan Villanueva [Website](http://www.juankafka.com)
* Lynne Yun [Website](http://www.lynneyun.com)
* Gen Ramirez [Website](https://genramirez.com)

Some timely advice on serif design (bigger!) was provided by:

* David Jonathan Ross [Website](https://djr.com)

Additional design advice as part of the _Type Masters_ program was provided by:

* Troy Leinster [Website](https://www.leinstertype.com/typemasters)

This project is dedicated to the memory of Donald Welch. A shame you never got to see it finished.

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://d-sargent.github.io/platypi.

## Changelog

**February 2024. Version 1.20**
* Google Fonts Latin Plus Character Set completed

**January 2024. Version 1.00**
* Vertical metrics added
* Kerning added
* _Most_ Fontbakery fails corrected, a couple left I still can't work out...

**January 2024. Version 0.40**
* Support for Australian Indigenous languages added
* Support for Vietnamese language added

**December 2023. Version 0.30**
* Google Fonts Latin Core Character Set completed

**August 2023. Version 0.20**
* Redrawn design started and uploaded onto GitHub
* Upright roman design in light and extra bold weights
* Matching italic design in light and extra bold weights
* Reconfigured font metrics for larger x-height and shorter ascenders/descenders
* Streamlined serif design approach

**December 2022. Version 0.10**
* Original design created while studying at Type West

The initial design for Platypi was produced while completing a Certificate in Type Design at Type West / Letterform Archive [Website](https://letterformarchive.org/type-west-online/) in 2022. The project aimed to create a 'latin' wedge serif model suitable for long-form text applications. This original design featured multiple upright weights alongside a single-weight italic style. In 2023–24, all letterforms were redrawn after reflection and time away from the project, along with matching italic styles and additional language support. 

## Future plans

**Expanded language support**
* Add Sámi character set
* Add Pan African character set

**Variable fonts**
* Create variable version (weight axis)

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
