---
title: Preuve du théorème de Pythagore
slug: Web/MathML/Examples/MathML_Pythagorean_Theorem
tags:
  - Débutant
  - Education mathématique
  - Exemple
  - HTML5 Math
  - MathML
translation_of: Web/MathML/Examples/MathML_Pythagorean_Theorem
original_slug: Web/MathML/Exemples/MathML_Theoreme_de_Pythagore
---
<p>Nous allons prouver le théorème de Pythagore :</p>

<p><strong>Définition :</strong> dans un triangle rectangle, le carré de l'hypoténuse est égal à la somme des carrés des deux autres côtés (appelés cathètes). Ainsi, soient a et b les cathètes et c l'hypothénuse, on a <math> <mrow> <msup><mi> a </mi><mn>2</mn></msup> <mo> + </mo> <msup><mi> b </mi><mn>2</mn></msup> <mo> = </mo> <msup><mi> c </mi><mn>2</mn></msup> </mrow> </math>.</p>

<p><strong>Preuve :</strong> nous pouvons le prouver de façon algébrique en montrant que l'aire du grand carré est égale à l'aire du carré intérieur, ajoutée à l'aire des 4 triangles :</p>
<math>
  <mtable columnalign="right center left">
    <mtr>
      <mtd>
        <msup>
          <mrow>
            <mo> ( </mo>
            <mi> a </mi>
            <mo> + </mo>
            <mi> b </mi>
            <mo> ) </mo>
          </mrow>
          <mn> 2 </mn>
        </msup>
      </mtd>
      <mtd>
        <mo> = </mo>
      </mtd>
      <mtd>
        <msup>
          <mi> c </mi>
          <mn>2</mn>
        </msup>
        <mo> + </mo>
        <mn> 4 </mn>
        <mo> ⋅ </mo>
        <mo>(</mo>
        <mfrac>
          <mn> 1 </mn>
          <mn> 2 </mn>
        </mfrac>
        <mi> a </mi>
        <mi> b </mi>
        <mo>)</mo>
      </mtd>
    </mtr>
    <mtr>
      <mtd>
        <msup>
          <mi> a </mi>
          <mn>2</mn>
        </msup>
        <mo> + </mo>
        <mn> 2 </mn>
        <mi> a </mi>
        <mi> b </mi>
        <mo> + </mo>
        <msup>
          <mi> b </mi>
          <mn>2</mn>
        </msup>
      </mtd>
      <mtd>
        <mo> = </mo>
      </mtd>
      <mtd>
        <msup>
          <mi> c </mi>
          <mn>2</mn>
        </msup>
        <mo> + </mo>
        <mn> 2 </mn>
        <mi> a </mi>
        <mi> b</mi>
      </mtd>
    </mtr>
    <mtr>
      <mtd>
        <msup>
          <mi>a </mi>
          <mn>2</mn>
        </msup>
        <mo> + </mo>
        <msup>
          <mi> b </mi>
          <mn>2</mn>
        </msup>
      </mtd>
      <mtd>
        <mo> = </mo>
      </mtd>
      <mtd>
        <msup>
          <mi> c </mi>
          <mn>2</mn>
        </msup>
      </mtd>
    </mtr>
  </mtable>
</math>