---
layout: ontology_detail
id: cteno
title: Ctenophore Ontology
build:
  checkout: git clone https://github.com/obophenotype/ctenophore-ontology.git
  system: git
  path: src/ontology
  method: vcs
contact:
  email: cjmungall@lbl.gov
  label: Chris Mungall
description: An anatomical and developmental ontology for ctenophores (Comb Jellies)
domain: anatomy
homepage: https://github.com/obophenotype/ctenophore-ontology
products:
  - id: cteno.owl
dependencies:
 - id: uberon
 - id: ro
taxon:
  id: NCBITaxon:10197
  label: Ctenophore
tracker: https://github.com/obophenotype/ctenophore-ontology/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
---

An anatomical and developmental ontology for ctenophores (Comb Jellies).

<img alt="Haeckel Ctenophorae" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/42/Haeckel_Ctenophorae.jpg/440px-Haeckel_Ctenophorae.jpg"/>

This ontology is available as a standalone artefact, and is also available as part of Uberon composite-metaozoan
