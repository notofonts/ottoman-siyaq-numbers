## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[12] NotoSerifOttomanSiyaq-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 579:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifOttomanSiyaq/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, tifinagh, tai-le, math, todhri, coptic, hebrew, old-permic, duployan, canadian-aboriginal, syriac</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>ottoman-siyaq-numbers</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Name ID 6 'NotoSerifOttomanSiyaq-Regular' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ebira (Latn, 2,200,000 speakers), Igbo (Latn, 27,823,640 speakers), Mfumte (Latn, 79,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Cicipu (Latn, 44,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Gulay (Latn, 250,478 speakers), Belarusian (Cyrl, 10,064,517 speakers), Southern Kisi (Latn, 360,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Koonzime (Latn, 40,000 speakers), Kom (Latn, 360,685 speakers), Teke-Ebo (Latn, 260,000 speakers), Dan (Latn, 1,099,244 speakers), Avokaya (Latn, 100,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), South Central Banda (Latn, 244,000 speakers), Yala (Latn, 200,000 speakers), Nzakara (Latn, 50,000 speakers), Dii (Latn, 71,000 speakers), Basaa (Latn, 332,940 speakers), Ma’di (Latn, 584,000 speakers), Vute (Latn, 21,000 speakers), Han (Latn, 6 speakers), Makaa (Latn, 221,000 speakers), Kaska (Latn, 125 speakers), Fur (Latn, 1,230,163 speakers), Heiltsuk (Latn, 300 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Navajo (Latn, 166,319 speakers), Lugbara (Latn, 2,200,000 speakers), Mango (Latn, 77,000 speakers), Sar (Latn, 500,000 speakers), Ejagham (Latn, 120,000 speakers), Mundani (Latn, 34,000 speakers), Ekpeye (Latn, 226,000 speakers), Nateni (Latn, 100,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* u1ED08 (U+1ED08): X=348.0,Y=2.0 (should be at baseline 0?)

* u1ED08 (U+1ED08): X=348.0,Y=2.0 (should be at cap-height 0?)

* u1ED14 (U+1ED14): X=232.0,Y=1.5 (should be at baseline 0?)

* u1ED14 (U+1ED14): X=232.0,Y=1.5 (should be at cap-height 0?)

* u1ED16 (U+1ED16): X=628.5,Y=0.5 (should be at baseline 0?)

* u1ED16 (U+1ED16): X=628.5,Y=0.5 (should be at cap-height 0?)

* u1ED1B (U+1ED1B): X=599.0,Y=1.5 (should be at baseline 0?)

* u1ED1B (U+1ED1B): X=599.0,Y=1.5 (should be at cap-height 0?)

* u1ED1D (U+1ED1D): X=586.0,Y=0.5 (should be at baseline 0?)

* u1ED1D (U+1ED1D): X=586.0,Y=0.5 (should be at cap-height 0?)

* u1ED25 (U+1ED25): X=519.5,Y=1.0 (should be at baseline 0?)

* u1ED25 (U+1ED25): X=519.5,Y=1.0 (should be at cap-height 0?)

* u1ED39 (U+1ED39): X=586.0,Y=0.5 (should be at baseline 0?)

* u1ED39 (U+1ED39): X=586.0,Y=0.5 (should be at cap-height 0?)

* u1ED3C (U+1ED3C): X=255.0,Y=-1.0 (should be at baseline 0?)

* u1ED3C (U+1ED3C): X=255.0,Y=-1.0 (should be at cap-height 0?)

* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

* G (U+0047): X=519.0,Y=1.5 (should be at cap-height 0?)

* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

* Gbreve (U+011E): X=519.0,Y=1.5 (should be at cap-height 0?)

* uni0122 (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

* uni0122 (U+0122): X=519.0,Y=1.5 (should be at cap-height 0?)

* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at cap-height 0?)

* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

* comma (U+002C): X=114.0,Y=1.0 (should be at cap-height 0?)

* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

* g (U+0067): X=161.0,Y=-0.5 (should be at x-height 0?)

* g (U+0067): X=161.0,Y=-0.5 (should be at cap-height 0?)

* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

* gbreve (U+011F): X=161.0,Y=-0.5 (should be at cap-height 0?)

* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at cap-height 0?)

* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at cap-height 0?)

* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

* nine (U+0039): X=139.0,Y=2.0 (should be at cap-height 0?)

* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

* q (U+0071): X=412.5,Y=0.5 (should be at x-height 0?)

* q (U+0071): X=412.5,Y=0.5 (should be at cap-height 0?)

* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at cap-height 0?)

* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at cap-height 0?)

* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at cap-height 0?)

* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

* section (U+00A7): X=101.0,Y=2.0 (should be at cap-height 0?)

* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

* semicolon (U+003B): X=132.0,Y=1.0 (should be at cap-height 0?)

* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

* sterling (U+00A3): X=77.0,Y=1.0 (should be at cap-height 0?)

* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

* three (U+0033): X=334.5,Y=1.0 (should be at cap-height 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- u1ED13 + u1ED2E
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 1 | 11 | 115 | 6 | 118 | 0 | 
| 0% | 0% | 0% | 4% | 46% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
