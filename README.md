# Greek Dialect Corpus (GRDD)

A collection of raw text from various Greek dialects, released with the paper **"GRDD: A Dataset for Greek Dialectal NLP"** ([arXiv:2308.00802](https://arxiv.org/abs/2308.00802)). It contains data from the following varieties:

- Cypriot Greek
- Cretan Greek
- Pontic Greek
- Northern Greek
- Part of the Modern Greek Wikipedia

An extended version of this dataset, GRDD+, covering 10 varieties, is available at [GRDD+ repository link].

## Sources and Rights

The texts in this dataset come from four kinds of sources, each with a different rights status.

**1. Public-domain texts.** Older literary and traditional texts whose authors died long ago, such as Vitsentzos Kornaros's *Erotokritos* (17th century). The works themselves are in the public domain. Where a text was taken from a modern edition, the edition is acknowledged, and any rights in the editorial work remain with the editor.

**2. Texts included with permission.** Cretan translations of Ancient Greek tragedies and comedies by Mr Sfakianakis, whom we thank. They are included with the author's permission for non-commercial research use only and remain his intellectual property.

**3. Wikipedia texts.** Texts from the Modern Greek Wikipedia are available under the [Creative Commons Attribution-ShareAlike (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/) license. Attribution belongs to the Wikipedia contributors, and any reuse must follow the terms of that license.

**4. Texts harvested from the web.** The Cypriot data include texts from publicly accessible blogs, forums and websites. These texts remain the intellectual property of their authors. They were collected and are made available solely for scientific research, under the text and data mining exception for research purposes (Article 3 of Directive (EU) 2019/790, as transposed into Greek law 2121/1993 by Law 4996/2022). They have been pseudonymized as described below.

No copyright in any text is transferred, claimed or waived by the maintainers through its inclusion in this dataset.

## Data Collection

- All texts were collected from publicly accessible sources, without bypassing logins, paywalls or any other access restrictions. Private or restricted blogs were not collected.
- All web harvesting complied with the `robots.txt` directives of the respective websites.

## Privacy and Pseudonymization

To protect the privacy of individuals whose texts appear in the web-harvested data, the following measures have been applied:

- **Personal names** appearing in blog posts, comments and other user-generated content have been replaced with culturally appropriate pseudonyms. Morphological case agreement (nominative, genitive, accusative, vocative) has been preserved, including dialectal forms (e.g. the Cypriot accusative in -αν).
- **Blogger usernames and handles** have been replaced with pseudonyms, both in comment attribution lines and where bloggers refer to each other in running text, in Greek as well as Latin script. Inflection has been preserved.
- **URLs, email addresses, blog domain names and post metadata** (publication dates and times, comment counts, author credit lines) have been removed.
- **Blogging-platform interface text** (e.g. reply and delete buttons captured with the comments) has been removed.
- **Public figures** (politicians, historical figures) referenced in public discourse have been kept, as their mention concerns matters of public record.

A record of the original sources and of the pseudonym mapping is **not publicly released**. It is kept in secure storage by the maintainers for verification of published results and for handling removal requests. Access may be granted only to researchers, for verification purposes, under a written agreement that prohibits redistribution and re-identification.

## Terms of Use

By using this dataset you agree to the following:

- The dataset may be used only for **non-commercial** academic research, teaching and the reproduction of published results in linguistics, NLP and related fields.
- The original texts may not be republished or redistributed for commercial purposes, and may not be used to train or improve models offered commercially.
- You may not attempt to re-identify any person whose text or name appears in the dataset, or to link pseudonymized texts back to their authors or original sources.
- Quotations from the texts in publications should be short and limited to what the research requires.
- If you use this dataset in academic work, please cite the paper listed below and acknowledge the original authors of the texts.

## Removal Requests

If you are the author of a text included in this dataset, or a person named in it, and you want it removed or corrected, please write to **kafouroutsos@gmail.com**. We will remove or correct the material in the next update of the repository, and in any case within 30 days of the request. No justification is required.

## License

- **Annotations, metadata and code** are released under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.
- **Public-domain texts** (category 1) carry no copyright restrictions on the works themselves.
- **Wikipedia texts** (category 3) remain under CC BY-SA 4.0.
- **All other texts** (categories 2 and 4) are not licensed by the maintainers. They remain the property of their authors and are provided only for non-commercial research under the terms above.

## Disclaimer

The dataset is provided "as is", without warranty of any kind. The maintainers make no claim of ownership over texts they did not author and accept no liability for uses of the dataset that breach these terms.

## Citation

If you use this dataset, please cite:

```bibtex
@misc{chatzikyriakidis2023grdd,
  author = {Stergios Chatzikyriakidis and Chatrine Qwaider and Ilias Kolokousis and Christina Koula and Dimitris Papadakis and Efthymia Sakellariou},
  title  = {GRDD: A Dataset for Greek Dialectal NLP},
  year   = {2023},
  eprint = {2308.00802},
  archivePrefix = {arXiv}
}
```
