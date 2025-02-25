---
layout: page
---

Brane, a programmable application orchestration framework with a focus on privacy.

<div style="padding: 20px; text-align: center;">
  <img src="./assets/images/logo.png" width="300">
</div>

Regardless of the context and rationale, running distributed applications on geographically dispersed IT resources often comes with various technical and organizational challenges. If not addressed appropriately, these challenges may impede development, and in turn, scientific and business innovation. We have designed and developed Brane to support implementers in addressing these challenges. Brane makes use of containerization to encapsulate functionalities as portable building blocks. Through programmability, application orchestration can be expressed using intuitive domain-specific languages. As a result, end-users with limited or no programming experience are empowered to compose applications by themselves, without having to deal with the underlying technical details.

This site is split into a couple sub-sites, each with its own purpose:

[Brane: The manual](/manual) is aimed at the users of the framework. It documents how to setup a framework as an system administrator, how to write packages on BraneScript or Bakery as a software engineer and how to write workflows as a scientist. Basically, if you are using Brane as a finalized program, this is the documentation for you.

[Tutorial Materials](/tutorials) contains resources for past demos, workshops and tutorials hosted for the Brane project. These are useful as they contain additional examples, slides and other materials that may further one’s understanding for Brane.

If you are interested in the working on the framework itself as a developer the following resources, are often of good use:

[Brane Code Documentation](/brane) is the documentation for the code itself. It’s not really meant to be read from top to bottom, like the other books, but rather as a reference during development on existing code.

[Policy-reasoner Documentation](/policy-reasoner) is the same, but then for the policy-reasoner project

[Brane: A Specification](/specification) is the book for those who are intending to develop the framework or who want to know how it works. It documents the framework’s internal workings, as well as provides a specification for how services communicate so they may be replaced by custom software running on the individual domains (hence it being a framework). In general, if you will be doing development about some part of the framework, you should start here.

