---
layout: page
title: FAQ
---

* [The table of contents will go here]
{:toc}

## 1. What are the goals of the MathML association?

The goals of the MathML association are:

* Native implementation of the MathML language in all Web rendering engines.
* Development of software tools to let users read, write, search, store and
  transfer MathML formulas; with particular attention to make them accessible
  to people with disabilities.
* Usage of the MathML language to publish educational, technical and scientific
  content in Web sites, ebooks or Web apps.

For more details, take a look at our [Manifesto](/legal-documents/manifesto.html).

## 2. What are your plans to implement MathML in Web rendering engines?

Gecko (e.g. Firefox) and WebKit (e.g. Safari) are open source, have some MathML
support and there are developers from companies working on these rendering
engines who accept to review patches. Hence we will continue to collaborate
with them to fix bugs and improve the MathML support.

Blink (e.g. Chrome) is open source but Google has not expressed interest
to support native MathML until it becomes more popular on the Web and so the
short-term strategy is probably to develop a fork of Blink. Because the Blink
codebase is similar to WebKit, we can rely on the WebKit implementation. We
want to get in touch with other companies working on the Blink codebase
(Igalia, Opera, Vivaldi, etc).

Trident (Internet Explorer) is proprietary so we do not have any control on
the codebase. Microsoft has kept closing the requests for MathML support but
an implemention of "Office MathML" exists in Microsoft Office and could be
used for Trident. Hence we would like to convince Microsoft to give a this a
try.

## 3. Where can I vote for MathML support in Chrome and Internet Explorer?

Try to vote for [MathML in Chrome](https://code.google.com/p/chromium/issues/detail?id=152430), [MathML in Internet Explorer (developer feedback)](https://status.modern.ie/mathml) and [MathML in Internet Explorer (user feedback)](https://windows.uservoice.com/forums/265757-windows-feature-suggestions/suggestions/6592643-support-for-html5-s-mathml).

## 4. How is the MathML association different from the OpenMath Society?

As stated on the [OpenMath website](www.openmath.org), the goal of OpenMath Society is to "coordinate OpenMath activities" with focus on "semantic meaning or content" of mathematical formulas. The MathML association is instead focused on making MathML well-integrated into the Web platform and natively supported by Web browsers and assistive technologies.

That said, "the two technologies may be seen as highly complementary". OpenMath is strongly related to Content MathML and the &lt;semantics&gt; element can be used to provide MathML formulas with both presentation and meaning. The MathML manifesto highlights the importance of combining these two languages.

Many members of the Open Society are already involved in the MathML Association. We hope that more of them will support the MathML Manifesto and could become MathML affiliates.

## 5. How is the MathML association different from the MathJax Consortium?

As stated on the [MathJax website](https://www.mathjax.org), "The core of the MathJax project is the development of its state-of-the-art, open source, JavaScript platform for display of mathematics" while the MathML Association does not focus on a particular product but on native support everywhere.

We are happy that MathJax has already embraced MathML, which is used as its core formula representation language. While MathJax has provided an invaluable bridge solution for displaying beautiful math-on-the-web today, the MathML association is focusing on advancing the state of web mathematics tomorrow.

Our goal towards standards-compliant web mathematics, via native MathML support in all browsers, aims at faster rendering, better accessibility and towards building a healthy ecosystem of math web application development. [Quoting MathJax's Manager](http://exchanges.wiley.com/blog/2015/03/02/making-math-and-science-first-class-citizens-on-the-web/), "While we are proud of our accomplishments at MathJax, we know that we can only provide half the solution: native browser support must be the goal". Consequently, we hope that the MathJax Consortium will support our manifesto and could become a MathML affiliate.

## 6. How is the MathML association different from the W3C Math Working Group?

The [World Wide Web Consortium (W3C)](http://w3.org) is an "international community that
develops open standards to ensure the long-term growth of the Web". The
[Math working Group (Math WG)](http://www.w3.org/Math/) instantiates this to "facilitate
and promote the use of the Web for mathematical and scientific communication". The Math WG
has developed the MathML representation langauge for the presentation and content of
mathematical formulae since 1997, the current recommendation is
[MathML3](http://www.w3.org/TR/MathML3/) (April 2014), which was approved as ISO/IEC
International Standard in June 2015.

The MathML association wants to promote the standards (W3C recommendations) developed by
the W3C Math WG, support their implementation in web technologies, and raise public
awareness about MathML.
