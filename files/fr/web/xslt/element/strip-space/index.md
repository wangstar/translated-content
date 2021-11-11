---
title: strip-space
slug: Web/XSLT/Element/strip-space
tags:
  - Référence_XSLT
translation_of: Web/XSLT/Element/strip-space
original_slug: Web/XSLT/strip-space
---
<p>
{{ XsltRef() }}
</p><p>L'élément <code>&lt;xsl:strip-space&gt;</code> définit les éléments du document source dont les noeuds descendants ne contenant que des espaces doivent être supprimés.
</p>
<h3 id="Syntaxe"> Syntaxe </h3>
<pre class="eval">&lt;xsl:strip-space elements=LISTE-DE-NOMS-D-ÉLÉMENTS  /&gt;
</pre>
<h3 id="Attribut_obligatoire"> Attribut obligatoire </h3>
<dl><dt><code>elements</code>
</dt><dd>Définit une liste d'éléments du document source, séparés par des espaces, desquels les nœuds ne comportant que des espaces doivent être supprimés.
</dd></dl>
<h3 id="Attributs_optionnels"> Attributs optionnels </h3>
<p>Aucun.
</p>
<h3 id="Type"> Type </h3>
<p>Haut niveau, doit être l'enfant de <code>&lt;xsl:stylesheet&gt;</code> ou de <code>&lt;xsl:transform&gt;</code>.
</p>
<h3 id="D.C3.A9finition"> Définition </h3>
<p><a href="http://www.w3.org/TR/xslt#strip">XSLT 1.0, section 3.4</a>.
</p>
<h3 id="Support_Gecko"> Support Gecko </h3>
<p>Supporté.
</p>