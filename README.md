# Master's Thesis: Fuzzing Algorand Smart Contracts

This repository contains all the LaTeX files used to write the master's thesis.

## Background
Smart contracts are crucial for many blockchain networks, especially for sensitive financial transactions. Traditional testing methods, such as unit testing, are not fully effective for ensuring smart contract security because they do not consider the unique interactions between the contracts and the blockchain. A software testing technique called fuzzing, where random inputs are used to discover bugs, is emerging as a potent method for smart contract security. Tools like [Echidna](https://github.com/crytic/echidna) have applied fuzzing to Ethereum contracts with success. However, with the rise of newer blockchain platforms like [Algorand](https://algorand.com/), there's a need for dedicated security tooling.

## Contribution 
This paper introduces [**AlgoFuzz**](https://github.com/denispaluca/algofuzz), a fuzzing tool specifically designed for Algorand smart contracts. The tool uses greybox fuzzing to enhance code coverage and understand the possible states a contract can reach. The effectiveness of AlgoFuzz was tested using contracts from Echidna benchmarks and two larger Algorand contracts. In tests, AlgoFuzz achieved a code coverage of 64.04% on the Echidna benchmarks and 72.56% on the larger contracts, showcasing its potential to improve smart contract security on the Algorand platform.

## License

[![Creative Commons License][license-image]][license]

This template is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][license], meaning that:

 * You can share (copy, redistribute) and adapt (remix, transform, build upon) this template for any purpose, even commercially.
 * If you share the template or a modified (derived) version of it, you must attribute the template to the original authors ([Florian Walch and contributors][template-authors]) by providing a [link to the original template][template-url] and indicate if changes were made.
 * Any derived template has to use the [same][license] or a [compatible license][license-compatible].

The license **applies only to the template**; there are no restrictions on the resulting PDF file or the contents of your thesis.

[issue]: https://github.com/TUM-Dev/tum-thesis-latex/issues
[latex-wikibook]: https://en.wikibooks.org/wiki/LaTeX
[license-compatible]: https://creativecommons.org/compatiblelicenses
[license-image]: https://i.creativecommons.org/l/by-sa/4.0/88x31.png
[license]: https://creativecommons.org/licenses/by-sa/4.0/
[overleaf]: https://www.overleaf.com/
[sample-pdf]: https://raw.github.com/TUM-Dev/tum-thesis-latex/master/build/main.pdf
[overleaf-learn]: https://www.overleaf.com/learn
[tum-sharelatex]: https://sharelatex.tum.de/ldap/login
[template-authors]: https://github.com/TUM-Dev/tum-thesis-latex/graphs/contributors
[template-download]: https://github.com/TUM-Dev/tum-thesis-latex/archive/master.zip
[template-url]: https://github.com/TUM-Dev/tum-thesis-latex
[tex-se]: https://tex.stackexchange.com/
[thesis-guidelines]: https://www.in.tum.de/en/in/current-students/administrative-matters/thesis-guidelines-and-topics/
[wiki]: https://github.com/TUM-Dev/tum-thesis-latex/wiki/
