---
tags: [flavour-catalogue]
---
# Flavour Catalogue

This is the master catalogue of every coffee pod flavour known — tried and untried. It currently tracks **140 flavours** across **7 brands**, of which **18 have been tasted** (linked below, and detailed in the `Tasting Log/` folder).

> [!tip] At a glance
> Each row is a small card: the **dot** on the left shows roast (tan → near-black, purple = flavoured); the **badge** on the right is filled green once you've tasted it, hollow otherwise. A **clickable name** means it already has a page in `Tasting Log/` — click through to add a new session.

> [!info]- Enable the card styling (one-time)
> This catalogue uses a small CSS snippet (`flavour-catalogue.css`) for the dots/badges. It should already be enabled — if rows still look like plain bullet points, go to *Settings → Appearance → CSS snippets* and toggle **flavour-catalogue** on.

## ➕ Adding a new flavour you've spotted

Found a new pod at the store, or a new online listing? Add a line for it under the right Brand/Line/Collection section below (create the section if it's a brand-new line), using this format (also kept as [[New Flavour Row]] for quick copy-paste):

```
- <span class="roast-dot medium"></span> **Name** — *Taste profile* `Cup Size · Intensity` <span class="tried-badge"></span>
```

`roast-dot` can be `light`, `medium`, `dark`, `very-dark`, or `flavoured`. You don't need to create a page for it yet — leave the name as plain bold text until you actually taste it.

## 🤝 Adding a collaboration / limited edition

Collabs and limited drops (e.g. *Starbucks by Nespresso*, *Blue Bottle x Nespresso*, festive/seasonal releases) are still filed under their **Brand → Line** section like any other flavour — just use the collaboration's name as the *Collection*. They're also rounded up in the [Collaborations & Limited Editions](#-collaborations--limited-editions) section below so they're easy to spot. Add the same line there too when you log a new one.

## 🎯 Once you've tasted it

1. Duplicate [[New Tasting Log Entry]] from `Templates/` into `Tasting Log/` and rename it exactly after the flavour.
2. Fill in its frontmatter and category callout using this flavour's row in the catalogue.
3. Turn its name into a `[[link]]` here and add `tried` to its badge span's class — it'll switch to a filled green badge automatically.

---

## 🤝 Collaborations & Limited Editions

- <span class="roast-dot light"></span> **Blue Bottle Blend No. 1** — *Mild Ethiopia and Uganda blend, bright and delicate* `Gran Lungo · Int. 4` <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **Blue Bottle Bold Blend** — *Balanced cup with bright notes and smooth texture* `Mug · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Blue Bottle NOLA Style Blend** — *Chicory-flavoured, malted cereal and caramel, for iced* `Mug · Flavoured` <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **Blue Bottle Single Origin No. 1** — *Single origin, signature Blue Bottle brightness* `Gran Lungo · Int. 5` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **[[Sweet Almond and Hibiscus]]** — *Almond, caramel and vanilla with a floral hibiscus finish* `Espresso · Flavoured` <span class="tried-badge tried"></span>
- <span class="roast-dot dark"></span> **[[Caffe Florian]]** — *Dark chocolate, dried fruit and brown spices with woody, earthy notes* `Ristretto · Int. 9` <span class="tried-badge tried"></span>
- <span class="roast-dot flavoured"></span> **Gingerbread** — *Gingerbread flavoured* `Mug · Flavoured` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Peppermint Pinwheel** — *Peppermint chocolate flavoured* `Mug · Flavoured` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Pumpkin Spice Cake** — *Pumpkin spice flavoured* `Mug · Flavoured` <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **Starbucks Blonde (Original)** — *Soft, sweet and subtly tangy* `Espresso · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **Starbucks Blonde Espresso** — *Soft, sweet and subtly tangy double espresso* `Double Espresso · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **[[Starbucks Caffe Verona (O)]]** — *Roasty sweet with dark cocoa notes* `Espresso · Int. 11` <span class="tried-badge tried"></span>
- <span class="roast-dot dark"></span> **Starbucks Caffe Verona (V)** — *Roasty sweet with dark cocoa notes* `Mug · Int. 10` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Starbucks Colombia (Original)** — *Nutty with caramel notes, single origin* `Espresso · Int. 9` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Starbucks Colombia (Vertuo)** — *Nutty with caramel notes, single origin* `Gran Lungo · Int. 9` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Starbucks Decaf Espresso** — *Caramelly and smooth without caffeine* `Espresso · Int. 11` <span class="tag decaf">DECAF</span> <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **[[Starbucks Espresso (Original)]]** — *Caramelly and smooth, signature dark roast* `Espresso · Int. 11` <span class="tried-badge tried"></span>
- <span class="roast-dot dark"></span> **Starbucks Espresso Roast** — *Caramelly and smooth, signature dark roast* `Espresso · Int. 11` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **[[Starbucks House Blend (Original)]]** — *Balanced and smooth, rich everyday blend* `Lungo · Int. 7` <span class="tried-badge tried"></span>
- <span class="roast-dot dark"></span> **[[Starbucks Italian Style Roast]]** — *Roasty with sweet notes, rich and intense with caramelised sugar* `Espresso · Int. 11` <span class="tried-badge tried"></span>
- <span class="roast-dot medium"></span> **Starbucks Pike Place (Original)** — *Smooth with chocolate and toasted nut notes* `Lungo · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Starbucks Pike Place (Vertuo)** — *Smooth with subtle chocolate and toasted nut notes* `Mug · Int. 7` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Starbucks Sumatra (Vertuo)** — *Earthy and herbal with a full body* `Mug · Int. 11` <span class="tried-badge"></span>

---

## Blue Bottle

### Vertuo

**Blue Bottle x Nespresso**

- <span class="roast-dot light"></span> **Blue Bottle Blend No. 1** — *Mild Ethiopia and Uganda blend, bright and delicate* `Gran Lungo · Int. 4` <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **Blue Bottle Bold Blend** — *Balanced cup with bright notes and smooth texture* `Mug · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Blue Bottle NOLA Style Blend** — *Chicory-flavoured, malted cereal and caramel, for iced* `Mug · Flavoured` <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **Blue Bottle Single Origin No. 1** — *Single origin, signature Blue Bottle brightness* `Gran Lungo · Int. 5` <span class="tried-badge"></span>


## L'OR

### Original

**L'OR Espresso**

- <span class="roast-dot medium"></span> **L'OR Colombia** — *Fruity and aromatic single origin* `Espresso · Int. 9` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **L'OR Decaffeinated** — *Rich and intense without caffeine* `Espresso · Int. 9` <span class="tag decaf">DECAF</span> <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **L'OR Espresso** — *Full-bodied and intense* `Espresso · Int. 9` <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **L'OR Ethiopia** — *Floral and citrusy, delicate single origin* `Lungo · Int. 7` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **L'OR Forza** — *Bold and extra intense, very strong* `Espresso · Int. 9` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **L'OR Indonesia** — *Earthy, woody and full-bodied* `Espresso · Int. 8` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **L'OR Lungo Classique** — *Light, floral and smooth* `Lungo · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **L'OR Lungo Profondo** — *Rich and intense lungo* `Lungo · Int. 8` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **L'OR Ristretto** — *Rich and robust with a dense crema* `Ristretto · Int. 11` <span class="tried-badge"></span>


## Lavazza

### Original

**Lavazza Espresso**

- <span class="roast-dot medium"></span> **Lavazza Classico** — *Balanced and smooth with a mild body* `Espresso · Int. 8` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Lavazza Dek** — *Smooth and balanced, naturally decaffeinated* `Espresso · Int. 8` <span class="tag decaf">DECAF</span> <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Lavazza Intenso** — *Intense and full-bodied with cocoa notes* `Espresso · Int. 11` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Lavazza Lungo** — *Fruity flavour and a long-lasting finish* `Lungo · Int. 7` <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **Lavazza Qualita Oro** — *Fruity and floral, 100% Arabica from C&S America* `Espresso · Int. 8` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Lavazza Qualita Rossa** — *Dried fruit and soft chocolate, Arabica and Robusta* `Espresso · Int. 10` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Lavazza Ristretto** — *Short and strong with chocolate and caramel notes* `Ristretto · Int. 11` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Lavazza Tierra Bio** — *Smooth and aromatic, bio organic blend* `Espresso · Int. 9` <span class="tag organic">ORGANIC</span> <span class="tried-badge"></span>


## Luckin

### Original

**(Uncategorised)**

- <span class="roast-dot flavoured"></span> **Luckin Espresso Forte** — ** `—` <span class="tried-badge"></span>


## Nespresso

### Original

**Barista Creations Flavoured**

- <span class="roast-dot flavoured"></span> **Caramelizio** — *Caramel-flavoured, sweet and smooth* `Espresso · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Ciocattino** — *Dark chocolate-flavoured* `Espresso · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Cookie** — *Cookie-flavoured, for milk recipes* `Lungo · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Hazelino** — *Hazelnut-flavoured, rich and nutty* `Espresso · Int. 7` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Vanilla Eclair** — *Vanilla-flavoured, smooth and creamy* `Espresso · Int. 6` <span class="tried-badge"></span>

**Barista Creations For Milk**

- <span class="roast-dot light"></span> **Chiaro** — *For sweet and smooth recipes with milk* `For Milk · Light` <span class="tried-badge"></span>
- <span class="roast-dot very-dark"></span> **Corto** — *For extra intense recipes with milk, low acidity* `For Milk · Very Dark` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Scuro** — *For intense recipes with milk* `For Milk · Dark` <span class="tried-badge"></span>

**Classic**

- <span class="roast-dot medium"></span> **Capriccio** — *Aromatic and robust* `Espresso · Int. 5` <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **Cosi** — *Light and lemony* `Lungo · Int. 4` <span class="tried-badge"></span>
- <span class="roast-dot very-dark"></span> **Dharkan** — *Intense with bitterness and caramel notes* `Espresso · Int. 11` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Firenze Arpeggio Decaffeinato** — *Cocoa and roasted cereal* `Espresso · Int. 9` <span class="tag decaf">DECAF</span> <span class="tried-badge"></span>
- <span class="roast-dot very-dark"></span> **Kazaar** — *Syrupy and very powerful* `Ristretto · Int. 12` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **[[Livanto]]** — *Well-balanced with caramel notes* `Lungo · Int. 6` <span class="tried-badge tried"></span>
- <span class="roast-dot dark"></span> **Ristretto** — *Powerful and contrasted* `Ristretto · Int. 10` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Ristretto Decaffeinato** — *Powerful and contrasted* `Ristretto · Int. 10` <span class="tag decaf">DECAF</span> <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **Volluto** — *Sweet and smooth with biscuit notes* `Lungo · Int. 4` <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **Volluto Decaffeinato** — *Sweet and smooth* `Lungo · Int. 4` <span class="tag decaf">DECAF</span> <span class="tried-badge"></span>

**Festive Collection**

- <span class="roast-dot flavoured"></span> **[[Sweet Almond and Hibiscus]]** — *Almond, caramel and vanilla with a floral hibiscus finish* `Espresso · Flavoured` <span class="tried-badge tried"></span>

**Filter Style**

- <span class="roast-dot dark"></span> **Filter Style Intense** — *Roasted and smoky* `Filter · Dark` <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **Filter Style Mild** — *Fruity and mild cereal* `Filter · Light` <span class="tried-badge"></span>

**Ispirazione Italiana**

- <span class="roast-dot dark"></span> **Firenze Arpeggio** — *Cocoa and roasted cereal* `Espresso · Int. 9` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Genova Livanto** — *Balanced and round with caramel notes* `Espresso · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Milano** — *Well-rounded and rich* `Espresso · Int. 8` <span class="tried-badge"></span>
- <span class="roast-dot very-dark"></span> **Napoli** — *Very powerful and intensely roasted* `Ristretto · Int. 13` <span class="tried-badge"></span>
- <span class="roast-dot very-dark"></span> **Palermo Kazaar** — *Intense and spicy with pepper notes* `Espresso · Int. 12` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Roma** — *Slightly bitter with woody notes* `Espresso · Int. 8` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Torino Di Notte** — *Intense and velvety with bitter cocoa* `Espresso · Int. 10` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Venezia** — *Aromatic and balanced* `Espresso · Int. 8` <span class="tried-badge"></span>

**Limited Edition**

- <span class="roast-dot dark"></span> **[[Caffe Florian]]** — *Dark chocolate, dried fruit and brown spices with woody, earthy notes* `Ristretto · Int. 9` <span class="tried-badge tried"></span>

**Master Origins**

- <span class="roast-dot medium"></span> **Colombia (Original)** — *Fruity and balanced* `Lungo · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **Ethiopia (Original)** — *Floral and winey with fruit notes* `Lungo · Int. 4` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Guatemala** — *Balanced, cereal and biscuit notes* `Lungo · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot very-dark"></span> **India** — *Aromatic and intense with pepper notes* `Espresso · Int. 11` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Indonesia** — *Punchy and cereal with woody notes* `Espresso · Int. 7` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Nicaragua** — *Balanced with slight bitterness and caramel* `Lungo · Int. 8` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Peru Organic (Original)** — *Delicate and fruity, organic* `Lungo · Int. 6` <span class="tag organic">ORGANIC</span> <span class="tried-badge"></span>

**World Explorations**

- <span class="roast-dot light"></span> **Buenos Aires Lungo** — *Sweet and cereal* `Lungo · Int. 4` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Cape Town Lungo** — *Potent and roasted, woody* `Lungo · Int. 10` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Istanbul Espresso** — *Roasted with a hint of almond* `Espresso · Int. 8` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Paris Espresso** — *Cereal and biscuity* `Espresso · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Rio De Janeiro Espresso** — *Herbal and spicy* `Espresso · Int. 9` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Shanghai Lungo** — *Fruity with acidity* `Lungo · Int. 5` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Stockholm Lungo** — *Rich and full-bodied, malted* `Lungo · Int. 8` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Tokyo Lungo** — *Floral and complex* `Lungo · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Vienna Lungo** — *Round and smooth, malted cereal* `Lungo · Int. 6` <span class="tried-badge"></span>

### Vertuo

**Barista Creations Flavoured**

- <span class="roast-dot flavoured"></span> **Golden Caramel** — *Creamy and biscuity caramel* `Mug · Flavoured` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Rich Chocolate** — *Creamy and chocolatey* `Mug · Flavoured` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Roasted Hazelnut** — *Rich and nutty* `Mug · Flavoured` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Sweet Vanilla** — *Creamy and sweet vanilla* `Mug · Flavoured` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Sweet Vanilla Decaffeinato** — *Vanilla and creamy* `Mug · Flavoured` <span class="tag decaf">DECAF</span> <span class="tried-badge"></span>

**Barista Creations For Milk**

- <span class="roast-dot flavoured"></span> **Bianco Doppio** — *Sweet and milky, designed for milk* `Double Espresso · Flavoured` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Bianco Forte** — *Dark roasted and balanced, for milk* `Mug · Flavoured` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Bianco Piccolo** — *Sweet and smooth, designed for milk* `Espresso · Flavoured` <span class="tried-badge"></span>

**Barista Creations Over Ice**

- <span class="roast-dot flavoured"></span> [**Coconut Vanilla Over Ice** ](obsidian://open?vault=logspresso&file=Tasting%20Log%2FCoconut%20Vanilla%20Flavour%20Over%20Ice)— *Coconut and vanilla, for iced recipes* `Mug · Flavoured` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Ice Forte** — *Intense, for iced recipes* `Double Espresso · Flavoured` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **[[Ice Leggero]]** — *Mild, for iced recipes* `Double Espresso · Flavoured` <span class="tried-badge tried"></span>
- <span class="roast-dot flavoured"></span> **Pistachio Vanilla Over Ice** — *Pistachio and vanilla, for iced recipes* `Double Espresso · Flavoured` <span class="tried-badge"></span>

**Coffee+**

- <span class="roast-dot flavoured"></span> **Ginseng Delight** — *Soft caramel and ginseng* `Mug · Flavoured` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Melozio Go** — *Smooth and balanced, extra caffeine* `Mug · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Stormio Go** — *Rich and strong, extra caffeine* `Mug · Int. 8` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Vivida** — *Cereal and sweet, enriched with vitamin B6* `Mug · Int. 6` <span class="tried-badge"></span>

**Cold Brew Style**

- <span class="roast-dot dark"></span> **Cold Brew Style Intense** — *Sweet caramel* `355ml · Dark` <span class="tried-badge"></span>

**Craft Brew**

- <span class="roast-dot dark"></span> **Carafe Pour-Over Style** — *Roasted and smoky* `Carafe · Dark` <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **Carafe Pour-Over Style Mild** — *Mild and smooth* `Carafe · Light` <span class="tried-badge"></span>

**Double Espresso**

- <span class="roast-dot dark"></span> **Double Espresso Chiaro** — *Dense and wild* `Double Espresso · Int. 8` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **[[Double Espresso Chiaro Decaffeinato]]** — *Woody and toasted cereal* `Double Espresso · Int. 8` <span class="tag decaf">DECAF</span> <span class="tried-badge tried"></span>
- <span class="roast-dot medium"></span> **Double Espresso Dolce** — *Cereal and malted* `Double Espresso · Int. 5` <span class="tried-badge"></span>
- <span class="roast-dot very-dark"></span> **[[Double Espresso Scuro]]** — *Dark and bold* `Double Espresso · Int. 11` <span class="tried-badge tried"></span>

**Espresso**

- <span class="roast-dot dark"></span> **Altissio** — *Full-bodied and creamy* `Espresso · Int. 9` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **[[Altissio Decaffeinato]]** — *Full-bodied and creamy* `Espresso · Int. 9` <span class="tag decaf">DECAF</span> <span class="tried-badge tried"></span>
- <span class="roast-dot very-dark"></span> **[[Diavolitto]]** — *Highly intense and powerful* `Espresso · Int. 11` <span class="tried-badge tried"></span>
- <span class="roast-dot very-dark"></span> **Il Caffe** — *Intense and velvety* `Espresso · Int. 11` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **[[Orafio]]** — *Caramel and roasted* `Espresso · Int. 6` <span class="tried-badge tried"></span>
- <span class="roast-dot very-dark"></span> **Ristretto Intenso** — *Spicy and woody* `Ristretto · Int. 12` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Toccanto** — *Berry and winey* `Espresso · Int. 5` <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **[[Voltesso]]** — *Light and sweet* `Espresso · Int. 4` <span class="tried-badge tried"></span>

**Gran Lungo**

- <span class="roast-dot medium"></span> **Arondio** — *Cereal and mild* `Gran Lungo · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Fortado** — *Intense and full-bodied* `Gran Lungo · Int. 8` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Fortado Decaffeinato** — *Intense and full-bodied* `Gran Lungo · Int. 8` <span class="tag decaf">DECAF</span> <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **Inizio** — *Floral and cereal* `Gran Lungo · Int. 4` <span class="tried-badge"></span>

**Master Origins**

- <span class="roast-dot medium"></span> **[[Colombia]]** — *Fruity and winey* `Mug · Int. 5` <span class="tried-badge tried"></span>
- <span class="roast-dot medium"></span> **Costa Rica** — *Malty and cereal* `Gran Lungo · Int. 7` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **El Salvador** — *Sweet and jammy* `Mug · Int. 5` <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **[[Ethiopia]]** — *Floral and delicate* `Gran Lungo · Int. 4` <span class="tried-badge tried"></span>
- <span class="roast-dot medium"></span> **Mexico** — *Woody and spicy* `Mug · Int. 7` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Peru Organic** — *Fruity and elegant* `Espresso · Int. 6` <span class="tag organic">ORGANIC</span> <span class="tried-badge"></span>

**Mug**

- <span class="roast-dot medium"></span> **Half Caffeinato** — *Sweet and velvety, half caffeine* `Mug · Int. 5` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **[[Intenso]]** — *Intensely roasted, brown sugar notes* `Mug · Int. 9` <span class="tried-badge tried"></span>
- <span class="roast-dot medium"></span> **[[Melozio]]** — *Smooth and balanced* `Mug · Int. 6` <span class="tried-badge tried"></span>
- <span class="roast-dot medium"></span> **Melozio Decaffeinato** — *Toasted cereal and biscuity* `Mug · Int. 6` <span class="tag decaf">DECAF</span> <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Odacio** — *Toasted cereal and fruity* `Mug · Int. 7` <span class="tried-badge"></span>
- <span class="roast-dot light"></span> **Solelio** — *Fruity and citrus* `Mug · Int. 2` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Stormio** — *Spicy and woody* `Mug · Int. 8` <span class="tried-badge"></span>

**Seasonal**

- <span class="roast-dot flavoured"></span> **Gingerbread** — *Gingerbread flavoured* `Mug · Flavoured` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Peppermint Pinwheel** — *Peppermint chocolate flavoured* `Mug · Flavoured` <span class="tried-badge"></span>
- <span class="roast-dot flavoured"></span> **Pumpkin Spice Cake** — *Pumpkin spice flavoured* `Mug · Flavoured` <span class="tried-badge"></span>

**XL**

- <span class="roast-dot light"></span> **Alto Ambrato** — *Sweet caramel and toasted cereal* `XL · Int. 4` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Alto Onice** — *Roasted and woody* `XL · Int. 7` <span class="tried-badge"></span>


## Starbucks

### Original

**Starbucks by Nespresso**

- <span class="roast-dot light"></span> **Starbucks Blonde (Original)** — *Soft, sweet and subtly tangy* `Espresso · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **[[Starbucks Caffe Verona (O)]]** — *Roasty sweet with dark cocoa notes* `Espresso · Int. 11` <span class="tried-badge tried"></span>
- <span class="roast-dot medium"></span> **Starbucks Colombia (Original)** — *Nutty with caramel notes, single origin* `Espresso · Int. 9` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Starbucks Decaf Espresso** — *Caramelly and smooth without caffeine* `Espresso · Int. 11` <span class="tag decaf">DECAF</span> <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **[[Starbucks Espresso (Original)]]** — *Caramelly and smooth, signature dark roast* `Espresso · Int. 11` <span class="tried-badge tried"></span>
- <span class="roast-dot medium"></span> **[[Starbucks House Blend (Original)]]** — *Balanced and smooth, rich everyday blend* `Lungo · Int. 7` <span class="tried-badge tried"></span>
- <span class="roast-dot dark"></span> **[[Starbucks Italian Style Roast]]** — *Roasty with sweet notes, rich and intense with caramelised sugar* `Espresso · Int. 11` <span class="tried-badge tried"></span>
- <span class="roast-dot medium"></span> **Starbucks Pike Place (Original)** — *Smooth with chocolate and toasted nut notes* `Lungo · Int. 6` <span class="tried-badge"></span>

### Vertuo

**Starbucks by Nespresso**

- <span class="roast-dot light"></span> **Starbucks Blonde Espresso** — *Soft, sweet and subtly tangy double espresso* `Double Espresso · Int. 6` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Starbucks Caffe Verona (V)** — *Roasty sweet with dark cocoa notes* `Mug · Int. 10` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Starbucks Colombia (Vertuo)** — *Nutty with caramel notes, single origin* `Gran Lungo · Int. 9` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Starbucks Espresso Roast** — *Caramelly and smooth, signature dark roast* `Espresso · Int. 11` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **Starbucks Pike Place (Vertuo)** — *Smooth with subtle chocolate and toasted nut notes* `Mug · Int. 7` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **Starbucks Sumatra (Vertuo)** — *Earthy and herbal with a full body* `Mug · Int. 11` <span class="tried-badge"></span>


## illy

### Original

**illy Espresso**

- <span class="roast-dot medium"></span> **illy Classico** — *Balanced with caramel, orange blossom and jasmine* `Espresso · Int. 7` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **illy Classico Decaf** — *Caramel and jasmine notes without caffeine* `Espresso · Int. 7` <span class="tag decaf">DECAF</span> <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **illy Forte** — *Bold and powerful with toasted bread and dark chocolate* `Espresso · Int. 11` <span class="tried-badge"></span>
- <span class="roast-dot dark"></span> **illy Intenso** — *Full-bodied and intense with cocoa and dried fruit* `Espresso · Int. 9` <span class="tried-badge"></span>
- <span class="roast-dot medium"></span> **[[Illy Lungo|illy Lungo]]** — *Smooth and balanced with floral notes* `Lungo · Int. 6` <span class="tried-badge tried"></span>


