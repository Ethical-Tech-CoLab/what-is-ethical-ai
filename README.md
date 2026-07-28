# What Is Ethical AI?

**Ethics, Ethical Technology, and Ethical International Relations for the Age of Intelligent Machines**

Ethical Tech CoLab · NYU School of Professional Studies Center for Global Affairs, in collaboration with Microsoft · July 2026

📄 **[Read the paper online](https://ethical-tech-colab.github.io/what-is-ethical-ai/)** · [On the CoLab site](https://ethical-tech-colab.github.io/website/publications/what-is-ethical-ai) · [Markdown source](REPORT.md)

---

What is ethics, and why did humanity invent it? What makes technology ethical, international relations ethical, and artificial intelligence ethical?

This is the Ethical Tech CoLab's foundational paper. It answers those questions in that order, on the conviction that the issue at the heart of artificial intelligence is **power** and that ethics is humanity's oldest and most tested answer to the problem of governing power. It traces ethics from the earliest civilizations through international affairs and human rights law to the responsible AI movement, the humanitarian sector, and the United Nations system, and closes with the motivation and research philosophy of the CoLab.

The answer it defends is **institutional rather than technical**. Ethical AI is not a product feature. It is artificial intelligence whose entire lifecycle stays accountable to ethical deliberation, to human rights as a floor, to the do no harm obligation, and to the participation of those the technology affects. No system is ethical in itself; systems are made ethical, or fail to be, by the institutions that govern them.

## The argument in four figures

| | |
| --- | --- |
| **84** | AI ethics guidelines mapped by Jobin, Ienca, and Vayena, converging on five principles but diverging on how to apply them |
| **118** | countries, overwhelmingly in the Global South, party to none of the major AI governance initiatives the UN surveyed |
| **15%** | of responses in the IRC's Signpost AI pilot could not be rated safe, the evaluators' basis for concluding the tool is not safe without a human in the loop |
| **$236B** | in annual illegal profits from forced labour, the ILO estimate that frames the CoLab's Forced Labor Structural Risk Index |

## Contents

1. Executive Summary
2. Humanity's Relationship with Power
3. What Is Ethics?
4. Why Humanity Created Ethics
5. From Custom to Universal Ethics
6. What Is Ethical International Relations?
7. What Is Ethical Tech?
8. What Is Ethical AI?
9. The Rise of Responsible AI
10. The Historical Evolution of AI in Humanitarian Work
11. Why Humanitarian AI Is Fundamentally Different
12. The International Affairs Context
13. Human Rights Foundations
14. The UN System's Evolving Approach to AI
15. The Ethical Tech CoLab
16. Conclusion

## Repository layout

```
REPORT.md                 the paper, canonical source
docs/index.html           generated Pages site (committed)
docs/pdf/                 the paper as a PDF (drop the designed PDF here)
scripts/build-site.mjs    REPORT.md -> docs/index.html
```

The designed PDF is not committed yet. Drop it in at `docs/pdf/What-Is-Ethical-AI-ETC-Report.pdf` and rerun the build: the download button on both the Pages site and the CoLab site lights up automatically once the file is present.

## Building the site

`REPORT.md` is the single source of truth. The Pages site is generated from it and the generated file is committed, so GitHub Pages serves `/docs` on the default branch directly, with no Actions workflow involved.

```bash
npm install
npm run build      # rewrites docs/index.html
```

Edit `REPORT.md`, run the build, and commit both.

## Citing this paper

> Ethical Tech CoLab (2026). *What Is Ethical AI? Ethics, Ethical Technology, and Ethical International Relations for the Age of Intelligent Machines.* Ethical Tech CoLab, NYU School of Professional Studies Center for Global Affairs, in collaboration with Microsoft.

## Licence

Text: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Code in `scripts/`: MIT.

---

The Ethical Tech CoLab is a research initiative of the NYU School of Professional Studies Center for Global Affairs, conducted in collaboration with Microsoft. Views and findings are those of the researchers and do not represent the official positions of New York University, Microsoft, or any partner institution. External programs cited are referenced as evidence, not as CoLab partnerships.
