<img style="float: right; width: 200px" src="../logo.png" />
# WikiPathways WP4

* WikiPathways: [WP4](https://identifiers.org/wikipathways:WP4)
* Scholia: [WP4](https://scholia.toolforge.org/wikipathways/WP4)
* WPRDF file: [wp/Human/WP4.ttl](../wp/Human/WP4.ttl)
* GPMLRDF file: [wp/gpml/Human/WP4.ttl](../wp/gpml/Human/WP4.ttl)
* SBML file: [sbml/WP4.sbml](../sbml/WP4.sbml) ([SVG](../sbml/WP4.svg)) ([conversion notes](../sbml/WP4.txt))

## Tests
* CASMetabolitesTests: all 2 tests OK!
* ChEBIMetabolitesTests: all 4 tests OK!
* ChemSpiderTests: all 2 tests OK!
* CovidDiseaseMapsTests
    * interactionsWithoutReferences: .x we found 1 problem(s):
        * [Interactions without literature references: 4](#2e295932)
    * missingHGNC: .. all OK!
* DataNodesTests
    * dataNodesWithoutIdentifier: .x we found 1 problem(s):
        * [The following DataNodes have no identifier: 3](#d2d32fa2)
    * unknownTypes_knownDatasource: .. all OK!
    * unknownTypes: .. all OK!
    * unknownTypes_Reactome: .. all OK!
* EnsemblTests: all 5 tests OK!
* GeneralTests
    * titlesShortEnough: .. all OK!
    * weirdCharacterTitles: .. all OK!
    * duplicateTitles: .. all OK!
    * curationAndHypothetical: .. all OK!
    * curationAndNeedsWork: .. all OK!
    * curationAndReactome: .. all OK!
    * noTags: .. all OK!
    * nullDataSources: .. all OK!
    * undefinedDataSources: .. all OK!
    * undefinedIdentifier: .x we found 1 problem(s):
        * [Data nodes with an 'undefined' identifier: 1](#fadcb642)
    * emptyLabelOfNodeWithIdentifier: .. all OK!
    * dataNodeWithoutGraphId: .. all OK!
    * groupsHaveDetail: .. all OK!
* GeneTests: all 3 tests OK!
* HMDBMetabolitesTests: all 2 tests OK!
* HMDBSecMetabolitesTests: all 3 tests OK!
* InteractionTests: all 7 tests OK!
* KEGGMetaboliteTests: all 2 tests OK!
* LIPIDMAPSTests: all 1 tests OK!
* MetabolitesTests
    * metaboliteAlsoOtherType: .. all OK!
    * casNumbersNotMarkedAsMetabolite: .. all OK!
    * chemspiderIDsNotMarkedAsMetabolite: .. all OK!
    * HMDBIDsNotMarkedAsMetabolite: .. all OK!
    * KEGGIDsNotMarkedAsMetabolite: .. all OK!
    * metabolitesWithAnEnsembleID: .x we found 1 problem(s):
        * [Unexpected metabolites with an Ensemble identifier: 3](#c300c046)
    * metabolitesWithAnEntrezGeneID: .. all OK!
    * metabolitesWithDbButNoIdentifier: .. all OK!
    * metabolitesWithIdentifierButNoDb: .. all OK!
    * ChEBIIDsNotMarkedAsMetabolite: .. all OK!
    * PubChemIDsNotMarkedAsMetabolite: .. all OK!
    * PubChemSubstanceIDsNotMarkedAsMetabolite: .. all OK!
    * PubChemIDsNotNumbers: .. all OK!
    * PubChemSubstanceIDsNotNumbers: .. all OK!
* MetaboliteStructureTests: all 2 tests OK!
* OudatedDataSourcesTests: all 7 tests OK!
* PathwayTests
    * deletedPathways: .. all OK!
    * linksToDeletedPathways: .. all OK!
    * speciesMismatch: .. all OK!
    * testRoundedRectangle: .x we found 1 problem(s):
        * [Pathways DataNodes with WikiPathways ID that can be converted to have a RoundedRectangle StyleType so that they become clickable: 1](#9fbad3cb)
    * youMustCite: .. all OK!
* ProteinsTests: all 2 tests OK!
* PubChemMetabolitesTests: all 3 tests OK!
* ReferencesTests: all 3 tests OK!
* UniProtTests: all 4 tests OK!
* WikidataTests: all 14 tests OK!


## Summary

* Number of test classes: 22
* Number of tests: 104
* Number of assertions: 210
* Number of fails: 5

## Fails

<a name="2e295932" />

## CovidDiseaseMapsTests.interactionsWithoutReferences

Interactions without literature references: 4
```
http://www.wikipathways.org/instance/WP4.gp_r119193 -> http://rdf.wikipathways.org/Pathway/WP4.gp_r119193/ComplexBinding/aa28d
http://www.wikipathways.org/instance/WP4.gp_r119193 -> http://rdf.wikipathways.org/Pathway/WP4.gp_r119193/WP/Interaction/iddb017374
http://www.wikipathways.org/instance/WP4.gp_r119193 -> http://rdf.wikipathways.org/Pathway/WP4.gp_r119193/WP/Interaction/id1b82938b
http://www.wikipathways.org/instance/WP4.gp_r119193 -> http://rdf.wikipathways.org/Pathway/WP4.gp_r119193/WP/Interaction/idd31b36db
```

More details at [https://wikipathways.github.io/WikiPathwaysCurator/CovidDiseaseMapsTests/interactionsWithoutReferences](https://wikipathways.github.io/WikiPathwaysCurator/CovidDiseaseMapsTests/interactionsWithoutReferences)

<a name="d2d32fa2" />

## DataNodesTests.dataNodesWithoutIdentifier

The following DataNodes have no identifier: 3
```
http://www.wikipathways.org/instance/WP4.gp_r119193 http://rdf.wikipathways.org/Pathway/WP4.gp_r119193/DataNode/d6c00 (ATP)
http://www.wikipathways.org/instance/WP4.gp_r119193 http://rdf.wikipathways.org/Pathway/WP4.gp_r119193/DataNode/f9e19 (Alpha-D-Glucose)
http://www.wikipathways.org/instance/WP4.gp_r119193 http://rdf.wikipathways.org/Pathway/WP4.gp_r119193/DataNode/da9a8 (D-Glucose)
```

<a name="fadcb642" />

## GeneralTests.undefinedIdentifier

Data nodes with an 'undefined' identifier: 1
```
[["mb","homepage","label"],
["http://rdf.wikipathways.org/Pathway/WP4.gp_r119193/DataNode/a489f","http://www.wikipathways.org/instance/WP4.gp_r119193","Substrate é"]
]
```

<a name="c300c046" />

## MetabolitesTests.metabolitesWithAnEnsembleID

Unexpected metabolites with an Ensemble identifier: 3
```
[["mb","label","identifier","pathway"],
["https://identifiers.org/ensembl/undefined","Substrate é","undefined","http://rdf.wikipathways.org/Pathway/WP4.gp_r119193/Complex/aa28d"],
["https://identifiers.org/ensembl/undefined","Substrate é","undefined","http://rdf.wikipathways.org/Pathway/WP4.gp_r119193/WP/Interaction/idd31b36db"],
["https://identifiers.org/ensembl/undefined","Substrate é","undefined","https://identifiers.org/wikipathways/WP4.gp_r119193"]
]
```

<a name="9fbad3cb" />

## PathwayTests.testRoundedRectangle

Pathways DataNodes with WikiPathways ID that can be converted to have a RoundedRectangle StyleType so that they become clickable: 1
```
http://www.wikipathways.org/instance/WP4.gp_r119193 -> d8bae, WP78
 ```

