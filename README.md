# MediCheck
Medicheck enables people to save money by finding cheaper, generic alternatives to branded medication.

## Value Proposition
Generic drugs are essentially copies of brand-name drugs. They have the exact same dosage, strength, routes of administration, and risks. Yet, they are often cheaper. A lot of money can potentially be saved from consuming generic drugs. As an example, Guardian's paracetamol tablet (20 per pack) retails at $2.90. The basic paracetamol tablet (also 20 per pack) sold by Panadol costs $7.20, which is 2.5 times the price of the Guardian tablets.

And this is a fair comparison. From the [Pharmaceutical Society of Singapore](https://www.pss.org.sg/know-your-medicines/commonly-asked-questions/generic-drug-cost#.Xr6zEcgzaUk):

> Generic medicines are chemically equivalent to patented medicines and are manufactured to the same safety and quality standards. For new generic medicines, the Health Sciences Authority requires the manufacturer to ensure that generics to be marketed are not just chemically equivalent, but also biologically equivalent (or bioequivalent) in the drug’s effect within the human body, usually to an acceptable limit (within +/- 20% for most medicines). With such a stringent regulation in Singapore, **there are no strong reasons to believe that innovators are more efficacious or safer compared to generic medicines.**

**TL;DR:** 500mg of paracetamol is 500mg of paracetamol, regardless of brand.

## OpenTechSG's Medium
MediCheck is delivered in the form of a webpage. The home page contains a set of links to dedicated pages for 7 popular drugs:

|   Drug    | What It Treats | Main Ingredient |
| :-------: | :------------- | :-------------: |
| Panadol   | Fever, muscle, and pain | Paracetamol |
| Nurofen   | Fever, pain, and inflammation | Ibuprofen |
| Clarityn  | Cold and eyes/nose/other allergy symptoms | Loratadine |
| Zyrtec    | Cold and eyes/nose/other allergy symptoms | Cetirizine |
| Telfast   | Allergy symptoms | Fexofenadine |
| Dulcolax  | Constipation | Bisacodyl |
| Fluimucil | Thick mucus | Acetylcysteine |

Each of the dedicated pages lists the alternative generic drugs for that given popular drug. The purpose is to provide easy access to the generic drugs to look out for when patients are at hospital and polyclinic pharmacies.

## To-do List

1. **EDA on drug data.** This is to explain how comparisons were made: using the dosage form, ingredients, strength, and route of administration. Also provides some facts about the pharma industry in SG.
2. **Develop site with Jekyll.** Pages required:
    1. Landing page with directory
    2. 7 x drug pages
    3. Value proposition / facts page
        1. Cost savings in the US
        2. Salient facts from EDA
    4. Suggestions page: for user requests for more generic drug lists
