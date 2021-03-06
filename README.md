
<h1>FUNGuild: Fungi + fUNctional + Guild</h>

http://funguild.org

http://stbates.org/funguild_db.php

**************************************

GENERAL NOTES

The FUNGuild bioinformatic tool is based on an original in-house python script referenced in Branco et al. 2013. PLoS One 8: 1–10 (http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0078295).

To run the FUNGuild bioinformatic tool locally, a current version of Python (https://www.python.org/) must be installed on the user’s local machine before the FUNGuild script (https://raw.githubusercontent.com/UMNFuN/FUNGuild/master/FUNGuild_v1.0.py) can be used. The FUNGuild database is accessed by the python script remotely and, therefore, does not need to be loaded to the user’s local machine. However, the script must be able to access the internet to connect with the database.

An online version of the FUNGuild bioinformatic tool, the 'assignment application', is also available here:

http://funguild.org (and the R shiny backend can be found here: http://github.com/thebateslab/funguild.shiny.backend/).

An example OTU table has been provided in the FUNGuild GitHub repository (https://github.com/UMNFuN/FUNGuild/blob/master/otu_table_example.txt) to demonstrate table formatting.

Queries to the FUNGuild DB can be carried out here:

https://thelab.shinyapps.io/fg_query/

CONTRIBUTING GUILD INFORMATION TO THE FUNGUILD DATABASE

- Data pertaining to particular fungal taxa can be submitted to the FUNGuild database as single (inputted via an online user interface - https://thelab.shinyapps.io/fg_entry/) or multiple (inputted online as a tab delimited text file - https://thelab.shinyapps.io/fg_upload/). All submitted entries will be reviewed by the database curators prior to being migrated to the main FUNGuild DB.

**************************************

Information should be entered into each FUNGuild database field, in sequence, as follows:

    •    Taxon: The scientific name (e.g., Ganoderma).

    •    Taxon Level: A numeral corresponding the correct taxonomic level of the taxon (1 = phylum, 2 = sub phylum, 3 = class, 4 = sub class, 5 = order, 6 = family, 7 = genus, 8 = species, 0 = keyword).

    •    Trophic Mode: One of three trophic categories [pathotroph = receiving nutrients at the expense of the host cells and causing disease (e.g., biotroph, parasite, pathogen, etc.); saprotroph = receiving nutrients by breaking down dead host cells (e.g., wood rotters, litter rotters, etc.); symbiotroph = receiving nutrients by exchanging resources with host cells (e.g., ectomycorrhiza, lichens, etc.)]. The concepts presented here are similar to those of Tedersoo et al. 2014. Global diversity and geography of soil fungi. Science 346(6213). DOI: 10.1126/science.1256688 (http://www.sciencemag.org/content/346/6213/1256688).

    •    Guild: Provide a relevant guild descriptor (e.g., "Algal Parasite", "Animal Gut", "Animal Pathogen", "Arbuscular Mycorrhizal", "Coprophilous", "Dark Septate Endophyte", "Ectomycorrhizal", "Endophyte", "Foliar Endophyte", "Ericoid Mycorrhizal", "Litter Saprotroph", "Lichenicolous", "Lichenized", "Musicolous", "Mycoparasite", "Plant Pathogen", "Soil Saprotroph", "Undefined Saprotroph", "Wood Saprotroph", etc.). New guilds can be erected if necessary.

    •    Confidence Ranking: "Highly Probable" (= absolutely certain), "Probable" (= fairly certain), "Possible" (= suspected but not proven, conflicting reports given, etc.).

    •    Growth Form: A basic morphological category such as "Agaricoid", "Boletoid", "Clavarioid", "Cup Fungus", "Facultative Yeast", "Gasteroid", "Hydnoid", " Jelly Fungus", "Phalloid", "Polyporoid", "Pyrenomycete", "Resupinate", "Rust", "Secotioid", "Smut", "Yeast", or "Thallus" should be noted.

    •    Trait: Other functional or morphological traits such as "Brown Rot", "Hypogeous", "Poisonous", "White Rot" or "Contact Exploration Type" would be appropriate for this field.

    •    Notes: Any other relevant information related to the taxon (e.g., "Facultative human pathogen causing coccidioidomycosis" for Coccidioides immitis, "Host - Arecaceae - Casuarinaceae, Palmae, Sapotaceae" for Xylaria obovata, or "Syn. Umbilicaria" for Actinogyra).

    •    Citation/Source: Publication, website, etc. from which the corresponding guild information was derived e.g.:
    
            Costa IPMW et al. 2012. Checklist of endophytic fungi from tropical regions. Mycotaxon 119:26
    
            Esslinger TL. 2014. North Dakota State University (http://www.ndsu.edu/pubweb/~esslinge/chcklst/chcklst7.htm)
    
            James TY et al. 2006. Nature 443:818-822
    
            Kurtzman CP, Fell JW, Boekhout T eds. 2011. The Yeasts, a Taxonomic Study. Fifth Edition. Vols 1-3. Elsevier, San Diego
    
            Tedersoo L, May TW, Smith ME. 2010. Mycorrhiza 20:217-263
    
            Outline of Ascomycota (http://www.fieldmuseum.org/myconet)
    
            http://www.apsnet.org/publications/commonnames/Pages/default.aspx
    
    *Data for taxa that is based on peer-reviewed publications is preferred.
    
**************************************

- Taxon entries proposed for addition to the database via the online 'crowd source' forms will be visible on the FUNGuild DB once they have been reviewed by the DB curators and migrated to the main database.

- Once migrated, proposed entries will automatically be available to all using the FUNGuild bioinformatic tool to make annotated assignments (e.g., guilds) to their OTU tables of fungal taxa.

