# Vaud: law history in git

The law of the canton of Vaud (Canton de Vaud, Switzerland) as a git history: one file per article, one commit per change on the day it took effect. `git blame` and `git log` work line by line; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-vd/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in French, the canton's official language, exactly as published.

## What this repository holds

594 acts with 1972 versions so far, starting with the cantonal constitution. Each act has every consolidated version the BLV publishes, from the act as adopted (where the BLV holds it) to today: the constitution first, then the cantonal laws (LOI) and the règlements (RÈGLEMENT) in force, each in the order of the systematic collection, added in parts. Arrêtés, decrees, agreements and repealed acts are not included yet.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `101-01-cst-vd/` | CONSTITUTION du Canton de Vaud (101.01) | 14 | each consolidated version: 14 April 2003 to 14 June 2026 |
| `125-15-lc-mvms/` | LOI d'application du concordat du 15 novembre 2007 instituant des mesures contre la violence lors de manifestations sportives (125.15) | 3 | each consolidated version: 1 January 2010 to 1 January 2014 |
| `132-15-ldecter/` | LOI sur le découpage territorial (132.15) | 11 | each consolidated version: 1 September 2006 to 1 January 2027 |
| `133-05-lopv/` | LOI sur l'organisation policière vaudoise (133.05) | 3 | each consolidated version: 1 January 2012 to 1 January 2025 |
| `133-11-lpol/` | LOI sur la police cantonale (133.11) | 11 | each consolidated version: 1 January 2003 to 1 September 2016 |
| `133-15-lpju/` | LOI sur la police judiciaire (133.15) | 5 | each consolidated version: 19 June 1995 to 1 January 2023 |
| `133-17-ldpju/` | LOI sur les dossiers de police judiciaire (133.17) | 4 | each consolidated version: 25 July 1989 to 1 September 2023 |
| `133-75-lpolc/` | LOI sur la police des chiens (133.75) | 3 | each consolidated version: 1 January 2008 to 1 May 2014 |
| `141-11-ldcv/` | LOI sur le droit de cité vaudois (141.11) | 1 | current text only, in force since 1 January 2018 |
| `142-01-lch/` | LOI sur le contrôle des habitants (142.01) | 9 | each consolidated version: 1 July 1984 to 1 January 2015 |
| `142-11-lvlei/` | LOI d'application dans le Canton de Vaud de la loi fédérale sur les étrangers et l'intégration (142.11) | 6 | each consolidated version: 1 January 2008 to 1 January 2021 |
| `142-21-lara/` | LOI sur l'aide aux requérants d'asile et à certaines catégories d'étrangers (142.21) | 8 | each consolidated version: 1 September 2006 to 1 July 2025 |
| `142-52-liepr/` | LOI sur l'intégration des étrangers et sur la prévention du racisme (142.52) | 1 | current text only, in force since 1 May 2007 |
| `160-01-ledp/` | LOI sur l'exercice des droits politiques (160.01) | 3 | each consolidated version: 1 January 2022 to 1 January 2027 |
| `170-11-lreca/` | LOI sur la responsabilité de l'Etat, des communes et de leurs agents (170.11) | 7 | each consolidated version: 1 July 1991 to 1 January 2014 |
| `170-21-linfo/` | LOI sur l'information (170.21) | 7 | each consolidated version: 1 September 2003 to 1 February 2017 |
| `170-31-lma/` | LOI sur la médiation administrative (170.31) | 3 | each consolidated version: 1 September 2009 to 1 January 2023 |
| `170-51-llv/` | LOI sur la législation vaudoise (170.51) | 1 | current text only, in force since 7 June 1977 |
| `170-52-lld/` | LOI sur la forme des lois et décrets (170.52) | 1 | current text only, in force since 6 December 1831 |
| `170-53-lplda/` | LOI sur la promulgation des lois, décrets et arrêtés (170.53) | 1 | current text only, in force since 1 December 1922 |
| `171-01-lgc/` | LOI sur le Grand Conseil (171.01) | 20 | each consolidated version: 1 July 2007 to 1 April 2026 |
| `172-115-loce/` | LOI sur l'organisation du Conseil d'Etat (172.115) | 8 | each consolidated version: 21 April 1998 to 1 January 2022 |
| `172-125-lr-ce/` | LOI sur la rémunération et les pensions des membres du Conseil d'Etat (172.125) | 7 | each consolidated version: 29 May 1990 to 1 March 2019 |
| `172-165-lpref/` | LOI sur les préfets et les préfectures (172.165) | 4 | each consolidated version: 1 January 2008 to 1 September 2016 |
| `172-31-lpers-vd/` | LOI sur le personnel de l'Etat de Vaud (172.31) | 10 | each consolidated version: 1 January 2004 to 1 February 2021 |
| `172-43-lcp/` | LOI sur la Caisse de pensions de l'Etat de Vaud (172.43) | 2 | each consolidated version: 1 November 2013 to 1 January 2014 |
| `172-45-llpp/` | LOI sur la prévoyance professionnelle de certaines catégories de personnel (172.45) | 6 | each consolidated version: 1 September 1998 to 1 January 2017 |
| `172-55-lemo/` | LOI chargeant le Conseil d'Etat de fixer, par voie d'arrêtés, les émoluments à percevoir pour les actes ou décisions émanant du Conseil d'Etat ou de ses départements (172.55) | 1 | current text only, in force since 1 January 1935 |
| `172-56-lfacmanif/` | LOI sur la facturation des prestations matérielles fournies par les services de l'Etat lors de manifestations (172.56) | 1 | current text only, in force since 1 July 2013 |
| `172-65-lprd/` | LOI sur la protection des données personnelles (172.65) | 5 | each consolidated version: 1 November 2008 to 1 September 2023 |
| `172-67-lcyber/` | LOI sur les moyens d’identification électronique et le portail sécurisé des prestations en ligne de l’Etat (172.67) | 1 | current text only, in force since 1 December 2020 |
| `172-68-lprds/` | LOI sur la protection des données personnelles dans le cadre de l'application de l'acquis de Schengen dans le domaine pénal (172.68) | 1 | current text only, in force since 1 September 2023 |
| `173-01-lojv/` | LOI d'organisation judiciaire (173.01) | 17 | each consolidated version: 1 January 2003 to 1 January 2024 |
| `173-05-lsam/` | LOI sur la computation des délais comprenant un samedi (173.05) | 2 | each consolidated version: 3 June 1966 to 1 September 2025 |
| `173-07-lcmag/` | LOI sur le Conseil de la magistrature (173.07) | 1 | current text only, in force since 1 January 2023 |
| `173-21-lmpu/` | LOI sur le Ministère public (173.21) | 2 | each consolidated version: 1 January 2011 to 1 January 2023 |
| `173-32-ljc/` | LOI sur la juridiction constitutionnelle (173.32) | 4 | each consolidated version: 1 January 2005 to 1 July 2013 |
| `173-33-lr-jc/` | LOI sur la rémunération et les pensions des juges cantonaux (173.33) | 6 | each consolidated version: 1 April 1990 to 1 January 2015 |
| `173-36-lpa-vd/` | LOI sur la procédure administrative (173.36) | 7 | each consolidated version: 1 January 2009 to 1 September 2025 |
| `173-61-ljt/` | LOI sur la juridiction du travail (173.61) | 1 | current text only, in force since 1 January 2011 |
| `173-63-lvleg/` | LOI d'application dans le Canton de Vaud de la loi fédérale du 24 mars 1995 sur l'égalité entre femmes et hommes (173.63) | 4 | each consolidated version: 1 October 2000 to 1 June 2021 |
| `173-655-ljb/` | LOI sur la juridiction en matière de bail (173.655) | 1 | current text only, in force since 1 January 2011 |
| `175-11-lc/` | LOI sur les communes (175.11) | 15 | each consolidated version: 1 January 2003 to 1 January 2022 |
| `175-51-lpiv/` | LOI sur la péréquation intercommunale (175.51) | 1 | current text only, in force since 1 January 2025 |
| `175-61-lfuscom/` | LOI sur les fusions de communes (175.61) | 6 | each consolidated version: 1 February 2005 to 1 July 2019 |
| `177-11-lpav/` | LOI sur la profession d'avocat (177.11) | 2 | each consolidated version: 1 January 2016 to 1 June 2023 |
| `178-11-lno/` | LOI sur le notariat (178.11) | 5 | each consolidated version: 1 January 2005 to 1 January 2011 |
| `179-11-lpag/` | LOI sur la profession d'agent d'affaires breveté (179.11) | 8 | each consolidated version: 1 June 2002 to 1 May 2020 |
| `180-05-lreedp/` | LOI sur les relations entre l'Etat et les Eglises reconnues de droit public (180.05) | 2 | each consolidated version: 1 January 2007 to 1 May 2010 |
| `180-11-leerv/` | LOI sur l'Eglise évangélique réformée du Canton de Vaud (180.11) | 1 | current text only, in force since 1 January 2007 |
| `180-12-lrfeacv/` | LOI portant reconnaissance de la Fédération des Eglises anglicanes et catholique chrétienne dans le Canton de Vaud (180.12) | 1 | current text only, in force since 1 July 2026 |
| `180-21-lfedec-vd/` | LOI sur la Fédération ecclésiastique catholique romaine du Canton de Vaud (180.21) | 1 | current text only, in force since 1 January 2007 |
| `180-41-lcilv/` | LOI sur la Communauté israélite de Lausanne et du Canton de Vaud (180.41) | 2 | each consolidated version: 1 January 2007 to 1 May 2010 |
| `180-51-lrcr/` | LOI sur la reconnaissance des communautés religieuses et sur les relations entre l'Etat et les communautés religieuses reconnues d'intérêt public (180.51) | 3 | each consolidated version: 1 January 2007 to 1 January 2011 |
| `916-125-lv/` | LOI sur la viticulture (916.125) | 8 | each consolidated version: 31 January 1992 to 1 September 2026 |
| `211-11-lec/` | LOI sur l'état civil (211.11) | 1 | current text only, in force since 1 February 2024 |
| `211-12-lovd/` | LOI d'organisation de la prévention et de la lutte contre la violence domestique (211.12) | 1 | current text only, in force since 1 November 2018 |
| `211-22-laje/` | LOI sur l'accueil de jour des enfants (211.22) | 11 | each consolidated version: 1 September 2006 to 1 January 2029 |
| `211-23-lvlpart/` | LOI d'application dans le Canton de Vaud de la loi fédérale sur le partenariat (211.23) | 2 | each consolidated version: 1 January 2007 to 1 January 2011 |
| `211-255-lvpae/` | LOI d’application du droit fédéral de la protection de l’adulte et de l’enfant (211.255) | 3 | each consolidated version: 1 January 2013 to 1 May 2017 |
| `211-42-lvldfr/` | LOI d'application de la loi fédérale du 4 octobre 1991 sur le droit foncier rural (211.42) | 6 | each consolidated version: 1 January 1994 to 1 January 2011 |
| `211-51-lvlfaie/` | LOI d'application de la loi fédérale du 16 décembre 1983 sur l'acquisition d'immeubles par des personnes à l'étranger (211.51) | 3 | each consolidated version: 1 January 1997 to 1 January 2011 |
| `211-61-lrf/` | LOI sur le registre foncier (211.61) | 3 | each consolidated version: 1 January 2013 to 1 January 2018 |
| `211-65-lcg/` | LOI sur le cadastre géologique (211.65) | 2 | each consolidated version: 1 July 2008 to 1 June 2013 |
| `221-307-lgbl/` | LOI sur les garanties en matière de baux à loyer (221.307) | 2 | each consolidated version: 15 May 1984 to 1 January 2009 |
| `221-313-lvlbfa/` | LOI d'application de la loi fédérale du 4 octobre 1985 sur le bail à ferme agricole (221.313) | 4 | each consolidated version: 29 November 2002 to 1 January 2011 |
| `221-315-lfocl/` | LOI sur l'utilisation d'une formule officielle au changement de locataire (221.315) | 2 | each consolidated version: 1 August 1993 to 1 January 2021 |
| `221-317-lvlcbd/` | LOI d'application de la loi fédérale du 23 juin 1995 sur les contrats-cadres de baux à loyer et leur déclaration de force obligatoire générale (221.317) | 1 | current text only, in force since 21 November 1997 |
| `221-41-lrc/` | LOI sur le registre du commerce (221.41) | 1 | current text only, in force since 1 February 2000 |
| `280-05-lvlp/` | LOI d'application dans le Canton de Vaud de la loi fédérale sur la poursuite pour dettes et la faillite (280.05) | 6 | each consolidated version: 1 January 2002 to 1 January 2018 |
| `280-21-lvlpdc/` | LOI concernant l'application dans le Canton de Vaud de la loi fédérale du 4 décembre 1947 réglant la poursuite pour dettes contre les communes et autres collectivités de droit public cantonal (280.21) | 1 | current text only, in force since 29 May 1951 |
| `311-15-lpen/` | LOI pénale vaudoise (311.15) | 7 | each consolidated version: 1 April 1970 to 1 July 2025 |
| `312-01-lvcpp/` | LOI d'introduction du Code de procédure pénale suisse (312.01) | 7 | each consolidated version: 30 December 2010 to 1 August 2023 |
| `312-05-lvppmin/` | LOI d'introduction de la loi fédérale du 20 mars 2009 sur la procédure pénale applicable aux mineurs (312.05) | 1 | current text only, in force since 1 January 2011 |
| `312-07-ledj/` | LOI sur l'exécution de la détention avant jugement (312.07) | 7 | each consolidated version: 1 January 2007 to 1 January 2019 |
| `312-11-lcontr/` | LOI sur les contraventions (312.11) | 2 | each consolidated version: 1 January 2011 to 2 January 2011 |
| `312-15-laoc/` | LOI sur les amendes d'ordre communales (312.15) | 1 | current text only, in force since 1 March 2016 |
| `312-41-lvlavi/` | LOI d'application de la loi fédérale du 23 mars 2007 sur l'aide aux victimes d'infractions (312.41) | 4 | each consolidated version: 1 May 2009 to 1 November 2018 |
| `340-01-lep/` | LOI sur l'exécution des condamnations pénales (340.01) | 9 | each consolidated version: 1 January 2007 to 1 January 2024 |
| `400-01-ls/` | LOI scolaire (400.01) | 7 | each consolidated version: 1 August 2003 to 1 August 2019 |
| `400-02-leo/` | LOI sur l’enseignement obligatoire (400.02) | 1 | current text only, in force since 1 August 2013 |
| `400-455-lepr/` | LOI sur l'enseignement privé (400.455) | 3 | each consolidated version: 1 June 2002 to 1 January 2007 |
| `412-11-less/` | LOI sur l'enseignement secondaire supérieur (412.11) | 5 | each consolidated version: 1 August 2003 to 1 January 2027 |
| `413-01-lvlfpr/` | LOI sur la formation professionnelle (413.01) | 2 | each consolidated version: 1 August 2009 to 1 April 2010 |
| `413-03-lmem/` | LOI sur la Fondation pour la formation et le perfectionnement professionnels des métiers machines, électrotechnique et métallurgie (413.03) | 3 | each consolidated version: 1 January 2004 to 1 January 2009 |
| `413-61-lopro/` | LOI sur l’orientation professionnelle (413.61) | 1 | current text only, in force since 1 September 2018 |
| `414-11-lul/` | LOI sur l'Université de Lausanne (414.11) | 5 | each consolidated version: 1 January 2005 to 1 July 2026 |
| `415-01-leps/` | LOI sur l'éducation physique et le sport (415.01) | 3 | each consolidated version: 1 August 2013 to 1 November 2025 |
| `416-11-laef/` | LOI sur l’aide aux études et à la formation professionnelle (416.11) | 5 | each consolidated version: 1 April 2016 to 1 January 2027 |
| `417-31-lps/` | LOI sur la pédagogie spécialisée (417.31) | 2 | each consolidated version: 1 August 2019 to 1 March 2022 |
| `419-01-lhev/` | LOI sur les hautes écoles vaudoises de type HES (419.01) | 4 | each consolidated version: 1 January 2014 to 1 August 2024 |
| `419-11-lhep/` | LOI sur la Haute école pédagogique (419.11) | 5 | each consolidated version: 1 September 2008 to 1 August 2026 |
| `431-01-lstat/` | LOI sur la statistique cantonale (431.01) | 5 | each consolidated version: 30 November 1999 to 1 January 2011 |
| `431-02-lvlhr/` | LOI d'application de la loi fédérale du 23 juin 2006 sur l'harmonisation des registres des habitants et d'autres registres officiels de personnes (431.02) | 4 | each consolidated version: 1 May 2010 to 1 October 2023 |
| `432-11-larch/` | LOI sur l’archivage (432.11) | 1 | current text only, in force since 1 January 2012 |
| `434-02-lfp10/` | LOI sur la fondation de droit public PLATEFORME 10 (434.02) | 2 | each consolidated version: 1 May 2020 to 1 January 2021 |
| `443-11-lcvl/` | LOI sur le cinéma, les vidéogrammes et les logiciels de loisirs (443.11) | 2 | each consolidated version: 1 December 2006 to 1 January 2009 |
| `444-01-lem/` | LOI sur les écoles de musique (444.01) | 1 | current text only, in force since 1 August 2012 |
| `446-11-lvca/` | LOI sur la vie culturelle et la création artistique (446.11) | 1 | current text only, in force since 1 May 2015 |
| `446-12-lpmi/` | LOI sur le patrimoine mobilier et immatériel (446.12) | 4 | each consolidated version: 1 May 2015 to 1 January 2025 |
| `449-11-lpresse/` | LOI sur la presse (449.11) | 4 | each consolidated version: 2 May 1989 to 1 May 2015 |
| `450-11-lprpnp/` | LOI sur la protection du patrimoine naturel et paysager (450.11) | 3 | each consolidated version: 1 January 2023 to 1 June 2025 |
| `451-15-lvoparcs/` | LOI d'application sur les parcs d'importance nationale (451.15) | 1 | current text only, in force since 1 March 2009 |
| `451-16-lprpci/` | LOI sur la protection du patrimoine culturel immobilier (451.16) | 2 | each consolidated version: 1 June 2022 to 1 March 2026 |
| `705-41-lpra/` | LOI sur la profession d'architecte (705.41) | 4 | each consolidated version: 7 April 1998 to 1 October 2021 |
| `831-41-lrp/` | LOI sur les Retraites Populaires (831.41) | 7 | each consolidated version: 1 January 1990 to 1 March 2020 |
| `850-41-lpromin/` | LOI sur la protection des mineurs (850.41) | 12 | each consolidated version: 1 January 2005 to 1 March 2024 |
| `850-43-lsaj/` | LOI sur la promotion et le soutien aux activités de jeunesse (850.43) | 2 | each consolidated version: 1 July 2010 to 1 January 2024 |
| `916-41-lvlfe/` | LOI d'application de la législation fédérale sur les épizooties (916.41) | 4 | each consolidated version: 1 March 1997 to 1 April 2023 |
| `916-42-lvossan/` | LOI d'application de l'ordonnance fédérale sur l'aide aux services de santé animale (916.42) | 1 | current text only, in force since 1 September 2023 |
| `963-41-laien/` | LOI concernant l'assurance des bâtiments et du mobilier contre l'incendie et les éléments naturels (963.41) | 5 | each consolidated version: 1 January 2000 to 1 March 2026 |
| `502-11-lvlarm/` | LOI sur les armes, les accessoires d'armes, les munitions et les substances explosibles (502.11) | 3 | each consolidated version: 17 November 2000 to 1 January 2009 |
| `510-11-lprop/` | LOI sur la protection de la population (510.11) | 4 | each consolidated version: 1 February 2005 to 1 January 2009 |
| `510-62-lgeo-vd/` | LOI sur la géoinformation (510.62) | 1 | current text only, in force since 1 January 2013 |
| `520-11-lvlpci/` | LOI d'exécution de la législation fédérale sur la protection civile (520.11) | 7 | each consolidated version: 24 September 1996 to 1 February 2015 |
| `524-11-lvlpbc/` | LOI d'application de la loi fédérale du 6 octobre 1966 sur la protection des biens culturels en cas de conflit armé (524.11) | 2 | each consolidated version: 1 July 1991 to 1 January 2011 |
| `818-51-lddc/` | LOI sur le subventionnement d'usines de destruction de cadavres d'animaux et déchets carnés (818.51) | 1 | current text only, in force since 9 March 1973 |
| `935-51-lvljar/` | LOI d'application de la loi fédérale du 29 septembre 2017 sur les jeux d'argent (935.51) | 1 | current text only, in force since 1 January 2021 |
| `610-11-lfin/` | LOI sur les finances (610.11) | 6 | each consolidated version: 1 January 2006 to 1 March 2024 |
| `610-15-lsubv/` | LOI sur les subventions (610.15) | 5 | each consolidated version: 1 January 2006 to 1 February 2018 |
| `610-20-lpecpm/` | LOI sur les participations de l'Etat et des communes à des personnes morales (610.20) | 3 | each consolidated version: 1 January 2006 to 1 March 2019 |
| `610-31-lre/` | LOI sur les receveurs (610.31) | 1 | current text only, in force since 1 January 1948 |
| `612-50-lafin/` | LOI sur l'assainissement financier au sens de l'article 165 de la Constitution du Canton de Vaud du 14 avril 2003 (612.50) | 2 | each consolidated version: 1 July 2010 to 1 January 2014 |
| `614-05-lccomptes/` | LOI sur la Cour des comptes (614.05) | 4 | each consolidated version: 1 January 2014 to 1 January 2023 |
| `614-11-lccf/` | LOI sur le Contrôle cantonal des finances (614.11) | 3 | each consolidated version: 1 July 2013 to 1 January 2023 |
| `642-00-011024-1/` | LOI sur l'impôt 2025 (642.00.011024.1) | 1 | current text only, in force since 1 January 2025 |
| `642-00-011024-2/` | LOI sur l'impôt 2026 (642.00.011024.2) | 1 | current text only, in force since 1 January 2026 |
| `642-11-li/` | LOI sur les impôts directs cantonaux (642.11) | 31 | each consolidated version: 1 January 2004 to 1 May 2026 |
| `642-12-lripp/` | LOI sur la réduction de l'impôt cantonal sur le revenu des personnes physiques (642.12) | 4 | each consolidated version: 1 January 2024 to 1 January 2027 |
| `642-21-lefi/` | LOI sur l'estimation fiscale des immeubles (642.21) | 6 | each consolidated version: 1 January 2001 to 1 January 2018 |
| `648-11-lmsd/` | LOI concernant le droit de mutation sur les transferts immobiliers et l'impôt sur les successions et donations (648.11) | 16 | each consolidated version: 1 January 2001 to 1 January 2025 |
| `648-21-ldsd/` | LOI sur la dation en paiement d'impôts sur les successions et donations (648.21) | 3 | each consolidated version: 1 January 2006 to 1 January 2009 |
| `650-11-licom/` | LOI sur les impôts communaux (650.11) | 14 | each consolidated version: 1 January 2004 to 1 January 2022 |
| `652-11-ltim/` | LOI sur le droit de timbre (652.11) | 1 | current text only, in force since 1 January 2014 |
| `658-51-lvlteo/` | LOI d'application de la législation fédérale sur la taxe d'exemption de l'obligation de servir (658.51) | 4 | each consolidated version: 15 January 1999 to 1 January 2013 |
| `814-68-lasp/` | LOI sur l'assainissement des sites pollués (814.68) | 6 | each consolidated version: 1 April 2006 to 1 April 2026 |
| `850-61-laih/` | LOI sur les mesures d'aide et d'intégration pour personnes handicapées (850.61) | 15 | each consolidated version: 1 January 2006 to 1 March 2026 |
| `935-61-lccr/` | LOI sur les campings et caravanings résidentiels (935.61) | 1 | current text only, in force since 1 January 1979 |
| `700-11-latc/` | LOI sur l'aménagement du territoire et les constructions (700.11) | 2 | each consolidated version: 1 September 2018 to 1 October 2020 |
| `701-43-llavaux/` | LOI sur le plan de protection de Lavaux (701.43) | 4 | each consolidated version: 1 July 1991 to 1 May 2022 |
| `710-01-le/` | LOI sur l'expropriation (710.01) | 3 | each consolidated version: 1 October 2000 to 1 October 2020 |
| `721-01-lpdp/` | LOI sur la police des eaux dépendant du domaine public (721.01) | 7 | each consolidated version: 1 January 2004 to 1 January 2026 |
| `721-03-lesdp/` | LOI réglant l'occupation et l'exploitation des eaux souterraines dépendant du domaine public cantonal (721.03) | 1 | current text only, in force since 12 May 1948 |
| `721-09-lml/` | LOI sur le marchepied le long des lacs et sur les plans riverains (721.09) | 4 | each consolidated version: 1 January 2004 to 1 September 2014 |
| `721-31-lde/` | LOI sur la distribution de l'eau (721.31) | 4 | each consolidated version: 1 August 1996 to 1 August 2013 |
| `725-01-lrou/` | LOI sur les routes (725.01) | 8 | each consolidated version: 1 January 2004 to 1 September 2018 |
| `726-01/` | LOI sur les marchés publics (LMP-VD) (726.01) | 1 | current text only, in force since 1 January 2023 |
| `730-01-lvlene/` | LOI sur l'énergie (730.01) | 8 | each consolidated version: 1 September 2006 to 1 January 2025 |
| `730-02-lrnss/` | LOI sur les ressources naturelles du sous-sol (730.02) | 1 | current text only, in force since 1 April 2019 |
| `730-11-lsecel/` | LOI sur le secteur électrique (730.11) | 1 | current text only, in force since 1 October 2009 |
| `731-01-llc/` | LOI sur l'utilisation des lacs et cours d'eau dépendant du domaine public (731.01) | 4 | each consolidated version: 1 January 1998 to 1 September 2014 |
| `732-11-lvlrcn/` | LOI d'application de la loi fédérale sur la responsabilité civile en matière nucléaire du 18 mars 1983 (732.11) | 2 | each consolidated version: 1 July 1991 to 1 January 2011 |
| `740-21-lmtp/` | LOI sur la mobilité et les transports publics (740.21) | 3 | each consolidated version: 30 January 2001 to 1 March 2026 |
| `741-01-lvcr/` | LOI sur la circulation routière (741.01) | 9 | each consolidated version: 1 October 1999 to 1 September 2022 |
| `741-11-ltvb/` | LOI sur la taxe des véhicules automobiles et des bateaux (741.11) | 1 | current text only, in force since 1 January 2024 |
| `743-05-lvch/` | LOI sur l'usage des véhicules à chenilles pendant l'hiver (743.05) | 1 | current text only, in force since 1 January 2022 |
| `747-21-lvlrb/` | LOI concernant l'application, dans le Canton de Vaud, de la loi fédérale du 28 septembre 1923 sur le registre des bateaux (747.21) | 2 | each consolidated version: 10 December 1924 to 1 January 2011 |
| `800-01-lsp/` | LOI sur la santé publique (800.01) | 23 | each consolidated version: 1 January 2004 to 1 February 2025 |
| `800-02-liflp/` | LOI sur l'interdiction de fumer dans les lieux publics (800.02) | 2 | each consolidated version: 15 September 2009 to 15 July 2024 |
| `801-11-lavasad/` | LOI sur l'Association vaudoise d'aide et de soins à domicile (801.11) | 3 | each consolidated version: 1 January 2010 to 1 January 2020 |
| `810-01-lpfes/` | LOI sur la planification et le financement des établissements sanitaires d'intérêt public (810.01) | 13 | each consolidated version: 1 January 2004 to 1 January 2026 |
| `810-02-lrs/` | LOI sur les réseaux de soins (810.02) | 1 | current text only, in force since 1 January 2008 |
| `810-04-lfr-ems/` | LOI sur le financement résiduel des soins de longue durée en EMS (810.04) | 2 | each consolidated version: 1 May 2012 to 1 January 2019 |
| `810-11-lhc/` | LOI sur les Hospices cantonaux (810.11) | 6 | each consolidated version: 1 December 2000 to 1 January 2024 |
| `814-11-lgd/` | LOI sur la gestion des déchets (814.11) | 7 | each consolidated version: 1 January 2007 to 1 January 2017 |
| `814-31-lpep/` | LOI sur la protection des eaux contre la pollution (814.31) | 8 | each consolidated version: 1 January 2004 to 1 May 2016 |
| `817-01-lvldai/` | LOI relative à l'exécution de la loi fédérale du 9 octobre 1992 sur les denrées alimentaires et les objets usuels (817.01) | 5 | each consolidated version: 1 January 2004 to 1 March 2020 |
| `821-01-lprcc/` | LOI sur la prévention et le règlement des conflits collectifs (821.01) | 2 | each consolidated version: 1 January 2004 to 1 January 2011 |
| `822-11-lemp/` | LOI sur l'emploi (822.11) | 9 | each consolidated version: 1 January 2006 to 1 April 2012 |
| `823-11-lrcep/` | LOI sur la constitution de réserves de crise par l'économie privée (823.11) | 1 | current text only, in force since 1 January 1952 |
| `823-15-lraf/` | LOI sur la constitution de réserves de crise bénéficiant d'allégements fiscaux (823.15) | 1 | current text only, in force since 1 January 1989 |
| `831-01-loai/` | LOI instituant l'office de l'assurance-invalidité pour le Canton de Vaud (831.01) | 5 | each consolidated version: 1 January 1999 to 1 January 2013 |
| `831-11-locc/` | LOI sur l'organisation de la Caisse cantonale de compensation (831.11) | 8 | each consolidated version: 1 January 1985 to 1 March 2019 |
| `831-21-lvpc/` | LOI sur les prestations complémentaires à l'assurance-vieillesse, survivants et invalidité (831.21) | 7 | each consolidated version: 1 January 2008 to 1 January 2025 |
| `832-01-lvlamal/` | LOI d'application vaudoise de la loi fédérale sur l'assurance-maladie (832.01) | 14 | each consolidated version: 1 January 2002 to 1 March 2026 |
| `836-01-lvlafam/` | LOI d'application de la loi fédérale sur les allocations familiales et sur des prestations cantonales en faveur de la famille (836.01) | 9 | each consolidated version: 1 January 2009 to 1 January 2023 |
| `836-11-lcsa/` | LOI réglant le paiement des allocations familiales et encourageant d'autres mesures de prévoyance sociale dans l'agriculture et la viticulture (Charte sociale agricole) (836.11) | 4 | each consolidated version: 1 July 1991 to 1 January 2018 |
| `840-11-ll/` | LOI sur le logement (840.11) | 7 | each consolidated version: 1 January 2001 to 1 February 2023 |
| `840-15-lpppl/` | LOI sur la préservation et la promotion du parc locatif (840.15) | 1 | current text only, in force since 1 January 2018 |
| `850-01-lof/` | LOI sur l'organisation et le financement de la politique sociale (850.01) | 15 | each consolidated version: 1 January 2005 to 1 January 2025 |
| `850-03-lhps/` | LOI sur l'harmonisation et la coordination de l'octroi des prestations sociales et d'aide à la formation et au logement cantonales vaudoises (850.03) | 7 | each consolidated version: 1 January 2013 to 1 January 2029 |
| `850-051-lasv/` | LOI sur l'action sociale vaudoise (850.051) | 18 | each consolidated version: 1 January 2006 to 1 March 2024 |
| `850-053-lpcfam/` | LOI sur les prestations complémentaires cantonales pour familles et les prestations cantonales de la rente-pont (850.053) | 11 | each consolidated version: 1 October 2011 to 1 February 2026 |
| `850-11-laprams/` | LOI d'aide aux personnes recourant à l'action médico-sociale (850.11) | 16 | each consolidated version: 1 May 2006 to 1 March 2026 |
| `850-36-lrapa/` | LOI sur le recouvrement et les avances sur pensions alimentaires (850.36) | 6 | each consolidated version: 1 January 2006 to 1 March 2024 |
| `900-01-lopr/` | LOI sur l'organisation professionnelle (900.01) | 1 | current text only, in force since 22 December 1944 |
| `900-05-lade/` | LOI sur l'appui au développement économique (900.05) | 4 | each consolidated version: 1 January 2008 to 1 June 2023 |
| `910-03-lvlagr/` | LOI sur l'agriculture vaudoise (910.03) | 3 | each consolidated version: 1 January 2011 to 1 January 2015 |
| `913-11-laf/` | LOI sur les améliorations foncières (913.11) | 7 | each consolidated version: 1 December 2003 to 1 January 2016 |
| `916-311-lgcb/` | LOI sur la procédure à suivre en matière de garantie dans le commerce du bétail (916.311) | 2 | each consolidated version: 1 January 1912 to 1 January 2011 |
| `921-01-lvlfo/` | LOI forestière (921.01) | 7 | each consolidated version: 1 January 2014 to 1 March 2026 |
| `922-03-lfaune/` | LOI sur la faune (922.03) | 8 | each consolidated version: 1 January 2003 to 1 April 2023 |
| `922-05-lvlpa/` | LOI d’application de la législation fédérale sur la protection des animaux (922.05) | 1 | current text only, in force since 1 January 2016 |
| `923-01-lpeche/` | LOI sur la pêche (923.01) | 6 | each consolidated version: 1 January 1994 to 1 January 2023 |
| `930-01-leae/` | LOI sur l'exercice des activités économiques (930.01) | 10 | each consolidated version: 1 January 2006 to 15 July 2024 |
| `931-15-lcar/` | LOI sur les carrières (931.15) | 3 | each consolidated version: 1 January 2004 to 1 June 2013 |
| `935-27-lesec/` | LOI sur les entreprises de sécurité (935.27) | 5 | each consolidated version: 1 January 1999 to 1 April 2015 |
| `935-28-ltsec/` | LOI sur le transport de sécurité de biens ou de valeurs (935.28) | 1 | current text only, in force since 1 February 2022 |
| `935-31-ladb/` | LOI sur les auberges et les débits de boissons (935.31) | 7 | each consolidated version: 1 January 2003 to 1 February 2026 |
| `941-21-lvmetr/` | LOI d'application de la législation fédérale sur la métrologie (941.21) | 1 | current text only, in force since 1 September 2021 |
| `943-05-lpros/` | LOI sur l'exercice de la prostitution (943.05) | 4 | each consolidated version: 1 September 2004 to 1 July 2021 |
| `943-11-lpr/` | LOI sur les procédés de réclame (943.11) | 7 | each consolidated version: 29 August 1995 to 15 July 2024 |
| `951-01-lbcv/` | LOI organisant la Banque Cantonale Vaudoise (951.01) | 5 | each consolidated version: 1 November 2002 to 1 March 2025 |
| `963-11-lpien/` | LOI sur la prévention des incendies et des dangers résultant des éléments naturels (963.11) | 2 | each consolidated version: 1 January 2000 to 1 January 2009 |
| `963-15-lsdis/` | LOI sur le service de défense contre l'incendie et de secours (963.15) | 4 | each consolidated version: 1 January 2011 to 1 January 2025 |
| `111-20-1-rf-interreg/` | RÈGLEMENT du Fonds cantonal Interreg (111.20.1) | 2 | each consolidated version: 1 May 2023 to 26 November 2025 |
| `120-15-rvlmsi/` | RÈGLEMENT d'application de la loi fédérale instituant des mesures visant au maintien de la sûreté intérieure (120.15) | 1 | current text only, in force since 1 August 2007 |
| `133-05-2-rocpol/` | RÈGLEMENT d'organisation de la conduite de l'organisation policière vaudoise (133.05.2) | 2 | each consolidated version: 1 January 2012 to 1 January 2013 |
| `133-05-3-rasp/` | RÈGLEMENT sur les compétences, l'organisation et les moyens des assistants de sécurité publique (133.05.3) | 1 | current text only, in force since 1 January 2012 |
| `133-11-1-rlpol/` | RÈGLEMENT d'application de la loi du 17 novembre 1975 sur la police cantonale (133.11.1) | 8 | each consolidated version: 16 December 2003 to 1 October 2019 |
| `133-12-1-re-pol/` | RÈGLEMENT fixant les frais dus pour certaines interventions de la police cantonale (133.12.1) | 6 | each consolidated version: 1 January 1996 to 1 November 2016 |
| `133-13-1-rise/` | RÈGLEMENT édictant des dispositions relevant du droit du travail pour les personnes participant à une investigation secrète (133.13.1) | 1 | current text only, in force since 1 November 2005 |
| `133-75-1-rlpolc/` | RÈGLEMENT d'application de la loi du 31 octobre 2006 sur la police des chiens (133.75.1) | 1 | current text only, in force since 1 May 2014 |
| `141-11-1-rldcv/` | RÈGLEMENT d’application de la loi du 19 décembre 2017 sur le droit de cité vaudois (141.11.1) | 2 | each consolidated version: 1 January 2018 to 1 October 2019 |
| `142-01-1-rlch/` | RÈGLEMENT d'application de la loi du 9 mai 1983 sur le contrôle des habitants (142.01.1) | 2 | each consolidated version: 16 December 2003 to 13 October 2020 |
| `142-11-1/` | RÈGLEMENT fixant les émoluments en matière de police des étrangers et d'asile (142.11.1) | 1 | current text only, in force since 1 September 2024 |
| `142-15-1-rvlmc/` | RÈGLEMENT concernant la Fondation romande de détention administrative LMC (142.15.1) | 1 | current text only, in force since 2 June 2000 |
| `142-21-1-rlara/` | RÈGLEMENT d'application de la loi du 7 mars 2006 sur l'aide aux requérants d'asile et à certaines catégories d'étrangers (142.21.1) | 1 | current text only, in force since 1 January 2022 |
| `142-21-5-rccasile/` | RÈGLEMENT sur la Commission consultative en matière d'asile (142.21.5) | 1 | current text only, in force since 1 June 2007 |
| `142-23-1-rf-ca/` | RÈGLEMENT sur le fonds pour le renforcement du financement cantonal en matière d'asile (142.23.1) | 1 | current text only, in force since 15 May 2000 |
| `142-52-1-rliepr/` | RÈGLEMENT d’application de la loi du 23 janvier 2007 sur l’intégration des étrangers et la prévention du racisme (142.52.1) | 1 | current text only, in force since 1 January 2008 |
| `160-01-1-rledp/` | RÈGLEMENT d'application de la loi du 5 octobre 2021 sur l'exercice des droits politiques (160.01.1) | 1 | current text only, in force since 1 January 2022 |
| `170-21-1-rlinfo/` | RÈGLEMENT d'application de la loi du 24 septembre 2002 sur l'information (170.21.1) | 4 | each consolidated version: 1 October 2003 to 1 January 2012 |
| `170-21-2-roji/` | RÈGLEMENT de l'ordre judiciaire sur l'information (170.21.2) | 7 | each consolidated version: 1 September 2006 to 1 October 2015 |
| `170-54-1-re-tdj/` | RÈGLEMENT fixant les émoluments concernant la transmission de données juridiques sur support électronique (170.54.1) | 1 | current text only, in force since 1 January 2002 |
| `171-01-1-rlgc/` | RÈGLEMENT d'application de la loi du 8 mai 2007 sur le Grand Conseil (171.01.1) | 5 | each consolidated version: 1 July 2007 to 1 September 2021 |
| `172-117-1-rcpro/` | RÈGLEMENT sur la Commission de prospective (172.117.1) | 1 | current text only, in force since 1 July 2024 |
| `172-165-1-rlpref/` | RÈGLEMENT d'application de la loi du 27 mars 2007 sur les préfets et les préfectures (172.165.1) | 1 | current text only, in force since 1 January 2008 |
| `172-215-1-rdea/` | RÈGLEMENT sur les départements de l'administration (172.215.1) | 2 | each consolidated version: 1 July 2022 to 1 June 2025 |
| `172-31-1-rlpers-vd/` | RÈGLEMENT d'application de la loi du 12 novembre 2001 sur le personnel de l'Etat de Vaud (172.31.1) | 14 | each consolidated version: 1 October 2003 to 1 February 2021 |
| `172-31-2-rform/` | RÈGLEMENT sur la formation continue (172.31.2) | 2 | each consolidated version: 1 January 2003 to 1 October 2018 |
| `172-31-3-rcpar/` | RÈGLEMENT sur la Commission paritaire (172.31.3) | 1 | current text only, in force since 1 January 2003 |
| `172-31-4-rcpers/` | RÈGLEMENT sur les commissions du personnel (172.31.4) | 1 | current text only, in force since 1 January 2003 |
| `172-31-5-roca/` | RÈGLEMENT sur l'organe de conciliation et d'arbitrage (172.31.5) | 1 | current text only, in force since 1 January 2003 |
| `172-31-6-rtripac/` | RÈGLEMENT sur le Tribunal de prud'hommes de l'Administration cantonale (172.31.6) | 2 | each consolidated version: 1 January 2003 to 1 July 2004 |
| `172-31-7-rpch/` | RÈGLEMENT relatif à la protection de la personnalité, à la gestion des conflits et à la lutte contre le harcèlement dans les relations de travail au sein de l'Etat de Vaud (172.31.7) | 1 | current text only, in force since 1 October 2024 |
| `172-31-8-rsst/` | RÈGLEMENT relatif à la protection de la santé et de la sécurité des collaborateurs au travail de l’Administration cantonale (172.31.8) | 1 | current text only, in force since 1 January 2017 |
| `172-315-1-rcf/` | RÈGLEMENT relatif à la classification des fonctions (172.315.1) | 4 | each consolidated version: 1 December 2008 to 1 July 2018 |
| `172-315-2-rsrc/` | RÈGLEMENT relatif au système de rétribution des collaborateurs de l’Etat de Vaud (172.315.2) | 6 | each consolidated version: 1 December 2008 to 7 July 2026 |
| `172-315-3-rrcm/` | RÈGLEMENT relatif à la rémunération de certains collaborateurs et magistrats de l’Etat de Vaud (172.315.3) | 6 | each consolidated version: 1 December 2008 to 1 January 2025 |
| `172-315-5-rcev-fonc/` | RÈGLEMENT sur la Commission d’évaluation des fonctions (172.315.5) | 2 | each consolidated version: 1 January 2014 to 1 April 2021 |
| `172-41-1-rapers/` | RÈGLEMENT sur l'assurance-accidents du personnel de l'Etat de Vaud (172.41.1) | 2 | each consolidated version: 1 January 2000 to 1 January 2007 |
| `172-55-1-re-adm/` | RÈGLEMENT fixant les émoluments en matière administrative (172.55.1) | 37 | each consolidated version: 15 March 2004 to 1 January 2026 |
| `172-57-1-raac/` | RÈGLEMENT relatif aux achats de l'Administration cantonale vaudoise (172.57.1) | 1 | current text only, in force since 1 October 2020 |
| `172-62-1-ric/` | RÈGLEMENT relatif à l’informatique cantonale (172.62.1) | 3 | each consolidated version: 1 January 2009 to 1 July 2026 |
| `172-65-1-rlprd/` | RÈGLEMENT d'application de la loi du 11 septembre 2007 sur la protection des données personnelles (172.65.1) | 2 | each consolidated version: 1 November 2008 to 1 April 2018 |
| `172-67-1-rlcyber/` | RÈGLEMENT d'application de la loi du 6 novembre 2018 sur les moyens d'identification électronique et le portail sécurisé des prestations en ligne de l'Etat (172.67.1) | 2 | each consolidated version: 1 December 2020 to 1 April 2026 |
| `172-71-1-rucl/` | RÈGLEMENT sur l'utilisation de la Cathédrale de Lausanne (172.71.1) | 3 | each consolidated version: 22 April 2002 to 1 December 2013 |
| `172-73-1-ruaa/` | RÈGLEMENT d'utilisation de l’amphithéâtre d'Avenches et autres monuments du site romain d'Aventicum (172.73.1) | 1 | current text only, in force since 1 June 2021 |
| `173-01-1-roj/` | RÈGLEMENT sur les offices judiciaires (173.01.1) | 3 | each consolidated version: 10 March 2004 to 1 January 2008 |
| `173-01-3-raoj/` | RÈGLEMENT d'administration de l'ordre judiciaire (173.01.3) | 11 | each consolidated version: 1 January 2008 to 1 April 2023 |
| `173-01-4-ramoj/` | RÈGLEMENT sur les autres activités lucratives des magistrats professionnels de l'ordre judiciaire (173.01.4) | 2 | each consolidated version: 1 July 2008 to 1 July 2023 |
| `173-01-6-rprooj/` | RÈGLEMENT sur la promesse solennelle des magistrats et collaborateurs de l'ordre judiciaire (173.01.6) | 2 | each consolidated version: 1 January 2008 to 1 January 2011 |
| `173-01-7-rpr/` | RÈGLEMENT sur le port de la robe judiciaire (173.01.7) | 6 | each consolidated version: 1 February 2005 to 1 April 2012 |
| `173-07-1-rcmag/` | RÈGLEMENT du Conseil de la magistrature (173.07.1) | 2 | each consolidated version: 1 May 2023 to 4 May 2026 |
| `173-07-2-re-cmag/` | RÈGLEMENT sur les émoluments, les frais et les dépens pour les procédures disciplinaires devant le Conseil de la magistrature (173.07.2) | 1 | current text only, in force since 2 September 2024 |
| `173-21-1-rofmpu/` | RÈGLEMENT d'organisation et de fonctionnement du Ministère public (173.21.1) | 2 | each consolidated version: 1 October 2024 to 17 April 2026 |
| `173-21-3-rprompu/` | RÈGLEMENT sur la promesse solennelle des collaborateurs du Ministère public (173.21.3) | 1 | current text only, in force since 1 February 2023 |
| `173-21-4-ripex/` | RÈGLEMENT sur l'indemnisation des procureurs extraordinaires et de leurs collaborateurs (173.21.4) | 1 | current text only, in force since 1 February 2023 |
| `173-21-5-rfpmpu/` | RÈGLEMENT sur les frais de procédure pour le Ministère public en matière administrative (173.21.5) | 1 | current text only, in force since 1 February 2023 |
| `173-31-1-rotc/` | RÈGLEMENT organique du Tribunal cantonal (173.31.1) | 15 | each consolidated version: 1 January 2008 to 1 October 2023 |
| `173-36-1-rcvepa/` | RÈGLEMENT sur la communication par voie électronique en procédure administrative (173.36.1) | 1 | current text only, in force since 1 December 2020 |
| `173-38-1-rotn/` | RÈGLEMENT organique du Tribunal neutre (173.38.1) | 1 | current text only, in force since 1 March 2006 |
| `173-63-1-rlvleg/` | RÈGLEMENT d'application de la loi du 24 juin 1996 d'application dans le Canton de Vaud de la loi fédérale du 24 mars 1995 sur l'égalité entre femmes et hommes (173.63.1) | 2 | each consolidated version: 1 July 2018 to 1 July 2020 |
| `173-71-1-rtm/` | RÈGLEMENT du Tribunal des mineurs (173.71.1) | 1 | current text only, in force since 1 May 2011 |
| `175-31-1-rccom/` | RÈGLEMENT sur la comptabilité des communes (175.31.1) | 4 | each consolidated version: 1 January 2004 to 1 January 2024 |
| `175-51-1-rlpiv/` | RÈGLEMENT d'application de la loi sur la péréquation intercommunale (175.51.1) | 1 | current text only, in force since 1 January 2025 |
| `175-516-r-rffa/` | RÈGLEMENT sur les modalités de répartition de la compensation fédérale visant à atténuer les effets de la mise en œuvre de la RFFA (175.516) | 2 | each consolidated version: 1 January 2020 to 1 January 2025 |
| `177-11-2-reav/` | RÈGLEMENT sur les examens d'avocat (177.11.2) | 1 | current text only, in force since 1 July 2016 |
| `177-11-3-rdsav/` | RÈGLEMENT sur le déroulement du stage d'avocat (177.11.3) | 1 | current text only, in force since 1 April 2016 |
| `177-11-4-re-chav/` | RÈGLEMENT sur les émoluments perçus par la Chambre des avocats ou son président, par délégation (177.11.4) | 2 | each consolidated version: 1 March 2008 to 1 January 2016 |
| `178-11-1-rlno/` | RÈGLEMENT d'application de la loi du 29 juin 2004 sur le notariat (178.11.1) | 7 | each consolidated version: 1 January 2005 to 1 January 2024 |
| `179-11-1-rlpag/` | RÈGLEMENT d'application de la loi du 20 mai 1957 sur la profession d'agent d'affaires breveté (179.11.1) | 1 | current text only, in force since 1 October 2013 |
| `179-11-4-reag/` | RÈGLEMENT concernant les épreuves pour l'obtention du brevet de capacité d'agent d'affaires breveté (179.11.4) | 2 | each consolidated version: 5 February 2002 to 1 September 2007 |
| `180-11-3-rclc/` | RÈGLEMENT sur les conditions de logement dans les cures propriété de l'Etat (180.11.3) | 1 | current text only, in force since 1 January 2001 |
| `180-51-1-rlrcr/` | RÈGLEMENT d'application de la loi du 9 janvier 2007 sur la reconnaissance des communautés religieuses et sur les relations entre l'Etat et les communautés religieuses reconnues d'intérêt public (180.51.1) | 1 | current text only, in force since 1 January 2015 |
| `180-51-5-rccreligieuse/` | RÈGLEMENT sur la Commission consultative en matière religieuse (180.51.5) | 2 | each consolidated version: 1 August 2015 to 1 January 2022 |
| `916-125-1-rlpv/` | RÈGLEMENT sur la limitation de la production et le contrôle officiel de la vendange (916.125.1) | 6 | each consolidated version: 18 June 2001 to 1 April 2021 |
| `916-125-2-rvv/` | RÈGLEMENT sur les vins vaudois (916.125.2) | 12 | each consolidated version: 1 June 2009 to 1 July 2026 |
| `916-125-2-1-re-ocv/` | RÈGLEMENT fixant les émoluments perçus par le Service de la viticulture et la Commission de dégustation des vins d'appellation d'origine contrôlée (916.125.2.1) | 2 | each consolidated version: 6 March 1996 to 1 January 2016 |
| `916-125-9-rblocvins/` | RÈGLEMENT sur le blocage – financement des vins vaudois (916.125.9) | 1 | current text only, in force since 1 February 2016 |
| `211-01-4-rmca/` | RÈGLEMENT sur les médiateurs civils agréés (211.01.4) | 5 | each consolidated version: 1 January 2011 to 1 May 2026 |
| `211-02-3-raj/` | RÈGLEMENT sur l'assistance judiciaire en matière civile (211.02.3) | 3 | each consolidated version: 1 January 2011 to 1 May 2019 |
| `211-02-4-rsemc/` | RÈGLEMENT sur la surveillance électronique en matière civile (211.02.4) | 1 | current text only, in force since 1 March 2022 |
| `211-11-1-rlec/` | RÈGLEMENT d'application de la loi du 25 novembre 1987 sur l'état civil (211.11.1) | 4 | each consolidated version: 1 January 2007 to 1 July 2022 |
| `211-12-1-rlovd/` | RÈGLEMENT d’application de la loi du 26 septembre 2017 d’organisation de la prévention et de la lutte contre la violence domestique (211.12.1) | 2 | each consolidated version: 1 November 2018 to 1 April 2021 |
| `211-22-1-rlaje/` | RÈGLEMENT d'application de la loi du 20 juin 2006 sur l'accueil de jour des enfants (211.22.1) | 1 | current text only, in force since 1 August 2019 |
| `211-255-1-ram/` | RÈGLEMENT concernant l'administration des mandats de protection (211.255.1) | 1 | current text only, in force since 1 January 2013 |
| `211-255-2-rcur/` | RÈGLEMENT sur la rémunération des curateurs (211.255.2) | 3 | each consolidated version: 1 January 2013 to 1 May 2019 |
| `211-255-4-rrmp/` | RÈGLEMENT sur le registre des mesures de protection (211.255.4) | 4 | each consolidated version: 1 January 2013 to 1 April 2020 |
| `211-42-1-rlvldfr/` | RÈGLEMENT concernant l'exécution de la loi du 13 septembre 1993 d'application de la loi fédérale du 4 octobre 1991 sur le droit foncier rural (211.42.1) | 3 | each consolidated version: 25 October 1995 to 18 August 2025 |
| `211-45-1-retr/` | RÈGLEMENT concernant l'engagement du bétail et la tenue des registres (211.45.1) | 1 | current text only, in force since 23 March 1994 |
| `211-51-1-rlvlfaie/` | RÈGLEMENT d'exécution de la loi d'application de la loi fédérale sur l'acquisition d'immeubles par des personnes à l'étranger (211.51.1) | 6 | each consolidated version: 11 October 2002 to 1 December 2021 |
| `211-61-1-re-rf/` | RÈGLEMENT fixant le tarif des émoluments du registre foncier (211.61.1) | 1 | current text only, in force since 1 July 2014 |
| `211-61-3-rirf/` | RÈGLEMENT sur la tenue informatique du registre foncier (211.61.3) | 1 | current text only, in force since 6 October 2009 |
| `280-05-2-rbcpf/` | RÈGLEMENT concernant les épreuves pour l'obtention du brevet de capacité de préposé aux poursuites et aux faillites (280.05.2) | 4 | each consolidated version: 23 April 1993 to 1 July 2008 |
| `280-05-3-rsq/` | RÈGLEMENT concernant les autorités et organes extraordinaires chargés d'ordonner et d'exécuter un séquestre en dehors des jours et des heures officiels d'ouverture des offices judiciaires (280.05.3) | 2 | each consolidated version: 23 December 1997 to 1 January 2011 |
| `312-01-5-rtmc/` | RÈGLEMENT du Tribunal des mesures de contrainte et d'application des peines (312.01.5) | 2 | each consolidated version: 1 November 2011 to 1 May 2018 |
| `312-05-5-rmppm/` | RÈGLEMENT sur la médiation dans le cadre de la procédure pénale applicable aux mineurs (312.05.5) | 1 | current text only, in force since 1 January 2011 |
| `312-25-1-rpeml/` | RÈGLEMENT fixant les indemnités pour les prestations et expertises médico-légales requises par les autorités administratives (312.25.1) | 1 | current text only, in force since 1 January 2026 |
| `322-51-1-rpdm/` | RÈGLEMENT sur l'attribution du pouvoir disciplinaire militaire (322.51.1) | 1 | current text only, in force since 15 November 2005 |
| `340-01-1-rspc/` | RÈGLEMENT sur le statut des personnes condamnées exécutant une peine privative de liberté ou une mesure (340.01.1) | 2 | each consolidated version: 1 January 2018 to 1 June 2026 |
| `340-01-2-rcic/` | RÈGLEMENT sur la Commission interdisciplinaire consultative concernant les délinquants dangereux (340.01.2) | 1 | current text only, in force since 1 March 2023 |
| `340-01-4-rcl/` | RÈGLEMENT pour le Comité des visiteurs de prisons et des lieux de privation de liberté (340.01.4) | 1 | current text only, in force since 26 May 2009 |
| `340-01-8-rprob/` | RÈGLEMENT sur les tâches et compétences de l'autorité de probation (340.01.8) | 3 | each consolidated version: 1 November 2009 to 9 May 2012 |
| `340-02-5-rsdaj/` | RÈGLEMENT sur le statut des personnes détenues placées en établissement de détention avant jugement (340.02.5) | 1 | current text only, in force since 1 January 2019 |
| `340-07-1-rdd/` | RÈGLEMENT sur le droit disciplinaire applicable aux personnes détenues avant jugement et condamnées (340.07.1) | 1 | current text only, in force since 1 January 2020 |
| `340-07-2-rddmin-vd/` | RÈGLEMENT sur le droit disciplinaire applicable aux personnes mineures et aux jeunes adultes détenus provisoirement ou faisant l’objet d’une condamnation prononcée en vertu du droit pénal des mineurs et détenues dans l’Etablissement de détention concordataire du Canton de Vaud (340.07.2) | 1 | current text only, in force since 20 June 2014 |
| `340-07-3-rsdmin/` | RÈGLEMENT sur le statut des personnes détenues placées dans un établissement de détention pour mineurs (340.07.3) | 3 | each consolidated version: 19 May 2014 to 1 January 2019 |
| `340-11-1-r-epo/` | RÈGLEMENT des Etablissements de la plaine de l'Orbe (340.11.1) | 2 | each consolidated version: 28 May 1993 to 1 January 2007 |
| `340-11-2-r-bm/` | RÈGLEMENT de la prison du Bois-Mermet à Lausanne (340.11.2) | 2 | each consolidated version: 11 March 1988 to 18 March 2008 |
| `340-11-3-r-emovl/` | RÈGLEMENT des maisons d'arrêts et de détention préventive d'Echallens, Morges, Orbe, Vevey et des salles d'arrêts de Lausanne (340.11.3) | 3 | each consolidated version: 11 March 1988 to 18 March 2008 |
| `340-11-4-ris-tuiliere/` | RÈGLEMENT sur le régime intérieur et le statut des personnes incarcérées dans la prison de La Tuilière (340.11.4) | 3 | each consolidated version: 12 June 1992 to 18 March 2008 |
| `340-11-5-rop-tuillere/` | RÈGLEMENT sur l'organisation et le personnel de la prison de La Tuilière (340.11.5) | 1 | current text only, in force since 12 June 1992 |
| `340-11-6-rsecep/` | RÈGLEMENT sur les agents de sécurité privée intervenant dans les établissements pénitentiaires (340.11.6) | 1 | current text only, in force since 1 February 2025 |
| `340-11-9-1-r-addiction/` | RÈGLEMENT concernant la Fondation latine Projets pilotes - Addictions (340.11.9.1) | 1 | current text only, in force since 1 June 2014 |
| `340-93-1-rasadultes/` | RÈGLEMENT concernant l’octroi d’autorisations de sortie aux personnes condamnées adultes et jeunes adultes (340.93.1) | 1 | current text only, in force since 1 January 2014 |
| `340-95-1-rasmineurs/` | RÈGLEMENT concernant l’octroi d’autorisations de sortie aux personnes condamnées mineures (340.95.1) | 1 | current text only, in force since 1 January 2014 |
| `340-95-2-rddmineurs/` | RÈGLEMENT concordataire sur le droit disciplinaire applicable aux personnes détenues pénalement ou placées dans des établissements fermés pour mineurs (340.95.2) | 1 | current text only, in force since 1 January 2014 |
| `340-95-3-rsd/` | RÈGLEMENT concordataire sur l'exécution des peines sous la forme de la semi-détention (340.95.3) | 2 | each consolidated version: 1 January 2018 to 1 June 2026 |
| `340-95-4-rtig/` | RÈGLEMENT concordataire sur l'exécution des peines sous la forme du travail d'intérêt général (340.95.4) | 2 | each consolidated version: 1 January 2018 to 1 June 2026 |
| `340-95-5-rese/` | RÈGLEMENT concordataire sur l'exécution des peines privatives de liberté sous surveillance électronique (340.95.5) | 2 | each consolidated version: 1 January 2018 to 1 June 2026 |
| `400-01-1-rls/` | RÈGLEMENT d'application de la loi scolaire du 12 juin 1984 (400.01.1) | 7 | each consolidated version: 1 March 2003 to 1 August 2026 |
| `400-01-1-3-ri-tp/` | RÈGLEMENT concernant les indemnités pour frais de transport et de pension des élèves de la scolarité obligatoire (400.01.1.3) | 2 | each consolidated version: 1 August 1986 to 1 August 2012 |
| `400-01-1-4-rts/` | RÈGLEMENT sur les transports scolaires (400.01.1.4) | 1 | current text only, in force since 1 August 2012 |
| `400-01-2-rpsps/` | RÈGLEMENT sur la promotion de la santé et la prévention en milieu scolaire (400.01.2) | 1 | current text only, in force since 1 August 2011 |
| `400-01-3-rcsps/` | RÈGLEMENT sur les constructions scolaires primaires et secondaires (400.01.3) | 1 | current text only, in force since 5 May 2020 |
| `400-02-1-rleo/` | RÈGLEMENT d’application de la loi du 7 juin 2011 sur l’enseignement obligatoire (400.02.1) | 9 | each consolidated version: 1 August 2013 to 1 August 2024 |
| `400-455-1-rlepr/` | RÈGLEMENT d'application de la loi du 12 juin 1984 sur l'enseignement privé (400.455.1) | 1 | current text only, in force since 1 August 1986 |
| `400-94-3-recds/` | RÈGLEMENT fixant les émoluments de la Conférence suisse des directrices et directeurs cantonaux de la santé (CDS) (400.94.3) | 1 | current text only, in force since 1 January 2008 |
| `400-97-3/` | RÈGLEMENT de la Commission de construction et du Comité de projet pour la réalisation de l’adaptation et l’extension du Gymnase intercantonal de la Broye (GYB) (400.97.3) | 1 | current text only, in force since 11 December 2018 |
| `405-31-2-rcsce/` | RÈGLEMENT relatif aux congés sabbatiques du corps enseignant et à leur financement (405.31.2) | 2 | each consolidated version: 1 March 2003 to 1 January 2010 |
| `412-11-1-rgy/` | RÈGLEMENT des gymnases (412.11.1) | 3 | each consolidated version: 1 August 2022 to 1 August 2025 |
| `412-11-2-1-rf-opti/` | RÈGLEMENT du fonds des taxes d'inscription de l'Office de perfectionnement scolaire, de transition et d'insertion professionnelle (412.11.2.1) | 2 | each consolidated version: 1 August 2004 to 15 December 2015 |
| `412-11-3-rf-egy/` | RÈGLEMENT des fonds des élèves des gymnases (412.11.3) | 2 | each consolidated version: 1 January 2000 to 1 September 2025 |
| `412-11-4-rtigy/` | RÈGLEMENT du fonds des taxes d'inscription des gymnases (412.11.4) | 1 | current text only, in force since 1 January 2000 |
| `412-12-1-rem/` | RÈGLEMENT de l'École de maturité (412.12.1) | 2 | each consolidated version: 1 August 2022 to 1 August 2023 |
| `413-01-1-rlvlfpr/` | RÈGLEMENT d'application de la loi du 9 juin 2009 sur la formation professionnelle (413.01.1) | 4 | each consolidated version: 1 August 2010 to 1 August 2026 |
| `413-01-3-rfeef/` | RÈGLEMENT sur la formation d'employé(e) en économie familiale (413.01.3) | 2 | each consolidated version: 1 August 2024 to 1 May 2025 |
| `413-03-1-rlmem/` | RÈGLEMENT d'application de la loi du 24 novembre 2003 sur la Fondation pour la formation et le perfectionnement professionnels des métiers machines, électrotechnique et métallurgie (MEM) (413.03.1) | 2 | each consolidated version: 1 April 2004 to 1 January 2006 |
| `413-04-1-recom/` | RÈGLEMENT de l'École de commerce (413.04.1) | 1 | current text only, in force since 1 August 2023 |
| `413-05-1-recg/` | RÈGLEMENT de l'École de culture générale (413.05.1) | 3 | each consolidated version: 1 August 2022 to 1 August 2025 |
| `413-073-1-rf-essante/` | RÈGLEMENT instituant un fonds d'encouragement de l'Ecole supérieure de la santé (ESSanté) (413.073.1) | 1 | current text only, in force since 1 January 2014 |
| `413-074-1-rf-eschbach/` | RÈGLEMENT création d'un fonds "Joseph et Berthe Eschbach Autier" pour l'attribution de bourses non remboursable à des étudiants et apprentis destinées à l'apprentissage des langues (413.074.1) | 1 | current text only, in force since 1 October 2023 |
| `414-11-1-rlul/` | RÈGLEMENT d'application de la loi du 6 juillet 2004 sur l'Université de Lausanne (414.11.1) | 5 | each consolidated version: 1 January 2014 to 1 May 2025 |
| `414-11-1-1-ra-ul/` | RÈGLEMENT sur les assistants à l'Université de Lausanne (414.11.1.1) | 1 | current text only, in force since 1 September 2007 |
| `414-11-1-2-rra-ul/` | RÈGLEMENT fixant la rémunération des assistants à l'Université de Lausanne (414.11.1.2) | 1 | current text only, in force since 1 January 2015 |
| `414-11-1-3-rti-ul/` | RÈGLEMENT sur les taxes d'immatriculation, d'inscription aux cours et aux examens perçues par l'Université de Lausanne (414.11.1.3) | 1 | current text only, in force since 1 July 2011 |
| `414-11-2-rvrr/` | RÈGLEMENT sur la valorisation des résultats de recherche au sein de l'Université de Lausanne et des Hospices cantonaux (414.11.2) | 1 | current text only, in force since 1 March 2009 |
| `414-11-3-rfin-lul/` | RÈGLEMENT d'application des dispositions financières de la loi du 6 juillet 2004 sur l'Université de Lausanne (414.11.3) | 1 | current text only, in force since 1 January 2012 |
| `414-11-4-rcm-ul/` | RÈGLEMENT sur l'admission des candidats étrangers aux études de médecine à l'Université de Lausanne (414.11.4) | 1 | current text only, in force since 1 January 2021 |
| `414-11-5-rceg-ul/` | RÈGLEMENT sur la construction, l’entretien et la gestion des immeubles et infrastructures mis à la disposition de l’Université de Lausanne (414.11.5) | 1 | current text only, in force since 17 October 2014 |
| `414-11-6-rfa-ul/` | RÈGLEMENT concernant le Fonds des acquisitions pour l'Université de Lausanne (414.11.6) | 1 | current text only, in force since 1 July 2017 |
| `415-01-1-rleps/` | RÈGLEMENT d'application de la loi du 18 décembre 2012 sur l'éducation physique et le sport (415.01.1) | 2 | each consolidated version: 1 August 2015 to 1 January 2018 |
| `416-11-1-rlaef/` | RÈGLEMENT d’application de la loi du 1er juillet 2014 sur l’aide aux études et à la formation professionnelle (416.11.1) | 4 | each consolidated version: 1 April 2016 to 1 January 2023 |
| `417-31-1-rlps/` | RÈGLEMENT d'application de la loi du 1er septembre 2015 sur la pédagogie spécialisée (417.31.1) | 2 | each consolidated version: 1 August 2019 to 24 August 2020 |
| `417-42-1-rgypad/` | RÈGLEMENT relatif aux formations gymnasiales pour adultes (417.42.1) | 3 | each consolidated version: 1 August 2022 to 1 August 2025 |
| `419-01-2-rlhev/` | RÈGLEMENT d’application de la loi du 11 juin 2013 sur les hautes écoles vaudoises de type HES (419.01.2) | 3 | each consolidated version: 1 January 2014 to 1 August 2025 |
| `419-01-3-rfin-hes/` | RÈGLEMENT sur la gestion financière et les normes comptables des hautes écoles cantonales de type HES (419.01.3) | 1 | current text only, in force since 1 January 2015 |
| `419-01-4-rparval/` | RÈGLEMENT sur la participation aux bénéfices générés par la valorisation des résultats de la recherche appliquée au sein des hautes écoles cantonales de type HES (419.01.4) | 1 | current text only, in force since 1 January 2015 |
| `419-01-5-ra-hev/` | RÈGLEMENT sur les assistants des hautes écoles cantonales vaudoises de type HES (419.01.5) | 2 | each consolidated version: 1 September 2015 to 1 August 2024 |
| `419-01-6-rcp-hev/` | RÈGLEMENT sur les cours préparatoires organisés par les hautes écoles vaudoises de type HES (419.01.6) | 2 | each consolidated version: 1 September 2015 to 1 November 2018 |
| `419-11-1-rlhep/` | RÈGLEMENT d’application de la loi du 12 décembre 2007 sur la Haute école pédagogique (419.11.1) | 8 | each consolidated version: 1 August 2009 to 1 August 2026 |
| `419-11-2-rfin-lhep/` | RÈGLEMENT d'application des dispositions financières de la loi du 12 décembre 2007 sur la Haute école pédagogique (419.11.2) | 2 | each consolidated version: 1 August 2009 to 1 December 2018 |
| `419-11-3-ra-hep/` | RÈGLEMENT sur les assistants à la Haute école pédagogique (419.11.3) | 2 | each consolidated version: 1 August 2010 to 1 August 2018 |
| `419-11-4-rpb-hep/` | RÈGLEMENT sur la participation aux bénéfices générés par la valorisation des résultats de la recherche appliquée au sein de la Haute école pédagogique (419.11.4) | 1 | current text only, in force since 1 August 2018 |
| `419-15-6-rf-sahep/` | RÈGLEMENT sur le fonds pour le soutien des activités culturelles, sociales ou sportives de la Haute école pédagogique (419.15.6) | 1 | current text only, in force since 1 September 2009 |
| `420-25-1-rgder/` | RÈGLEMENT sur la gestion du domaine de l'enseignement et de la recherche en biologie et en médecine par l'Université de Lausanne, le Centre hospitalier universitaire vaudois et la Policlinique médicale universitaire (420.25.1) | 3 | each consolidated version: 1 January 2006 to 1 May 2019 |
| `431-01-1-rlstat/` | RÈGLEMENT d'application de la loi du 15 septembre 1999 sur la statistique cantonale (431.01.1) | 4 | each consolidated version: 1 January 2004 to 1 October 2012 |
| `431-01-2-re-stat/` | RÈGLEMENT fixant les tarifs pour les prestations du Service cantonal de recherche et d'information statistiques (SCRIS) (431.01.2) | 1 | current text only, in force since 18 June 2001 |
| `431-02-1-rlvlhr/` | RÈGLEMENT relatif à la loi du 2 février 2010 d’application de la loi fédérale sur l’harmonisation des registres des habitants et d’autres registres officiels de personnes (431.02.1) | 1 | current text only, in force since 1 October 2014 |
| `432-11-1-rlarch/` | RÈGLEMENT d’application de la loi du 14 juin 2011 sur l’archivage (432.11.1) | 2 | each consolidated version: 1 January 2012 to 1 February 2014 |
| `433-11-1-rbcu/` | RÈGLEMENT de la Bibliothèque cantonale et universitaire - Lausanne (433.11.1) | 1 | current text only, in force since 1 May 2015 |
| `433-11-3-rf-bcu/` | RÈGLEMENT concernant le Fonds de la Bibliothèque cantonale et universitaire (433.11.3) | 1 | current text only, in force since 26 August 2002 |
| `433-11-4-rf-rero/` | RÈGLEMENT instituant un Fonds de coordination du réseau vaudois des bibliothèques affiliées au Réseau des bibliothèques romandes et tessinoises (RERO) (433.11.4) | 1 | current text only, in force since 26 August 2002 |
| `433-21-1-rf-frisch/` | RÈGLEMENT concernant le Fonds Thérèse Frisch (433.21.1) | 1 | current text only, in force since 26 August 2002 |
| `433-31-1-rf-christin/` | RÈGLEMENT concernant le Fonds Pierre Christin (433.31.1) | 1 | current text only, in force since 26 August 2002 |
| `434-01-1-rlmcb-a/` | RÈGLEMENT d’application de la loi du 18 mars 2014 pour la création d’une fondation de droit public pour le Musée cantonal des Beaux-Arts (mcb-a) (434.01.1) | 1 | current text only, in force since 1 January 2018 |
| `434-02-1-rlfp10/` | RÈGLEMENT d'application de la loi du 26 novembre 2019 sur la Fondation de droit public PLATEFORME 10 (434.02.1) | 1 | current text only, in force since 9 June 2020 |
| `434-02-2-rrcfp10/` | RÈGLEMENT de rémunération et indemnisation des membres du Conseil de la fondation de droit public PLATEFORME 10 (434.02.2) | 1 | current text only, in force since 16 March 2021 |
| `434-11-1-rf-masn/` | RÈGLEMENT concernant le Fonds des musées cantonaux d'archéologie et des sciences naturelles (434.11.1) | 1 | current text only, in force since 1 January 2026 |
| `434-21-1-rcmm/` | RÈGLEMENT du Château de Morges et ses musées (434.21.1) | 1 | current text only, in force since 1 November 2020 |
| `442-11-1-rf-david/` | RÈGLEMENT concernant le Fonds David (442.11.1) | 1 | current text only, in force since 26 August 2002 |
| `442-21-1-rf-decker/` | RÈGLEMENT concernant le Fonds des estampes du Professeur Decker (442.21.1) | 2 | each consolidated version: 26 August 2002 to 1 February 2007 |
| `442-41-1-r700p/` | RÈGLEMENT relatif à l'Atelier vaudois du 700e, à la Cité internationale des arts, à Paris (442.41.1) | 2 | each consolidated version: 3 May 1995 to 1 September 2018 |
| `443-11-1-rlcvl/` | RÈGLEMENT d'application de la loi du 27 juin 2006 sur le cinéma, les vidéogrammes et les logiciels de loisirs (443.11.1) | 1 | current text only, in force since 1 December 2006 |
| `444-01-1-rlem/` | RÈGLEMENT d'application de la loi du 3 mai 2011 sur les écoles de musique (444.01.1) | 2 | each consolidated version: 1 January 2012 to 1 May 2015 |
| `446-11-1-rf-cac/` | RÈGLEMENT concernant le Fonds cantonal des activités culturelles (446.11.1) | 2 | each consolidated version: 1 May 2015 to 1 September 2015 |
| `446-11-2-rf-cas/` | RÈGLEMENT concernant le Fonds cantonal des arts de la scène (446.11.2) | 2 | each consolidated version: 1 May 2015 to 1 September 2015 |
| `446-11-3-rf-csc/` | RÈGLEMENT concernant le Fonds cantonal de sensibilisation à la culture (446.11.3) | 1 | current text only, in force since 1 May 2015 |
| `446-11-4-raelc/` | RÈGLEMENT concernant l’aide à l’équipement de lieux culturels (446.11.4) | 1 | current text only, in force since 1 May 2015 |
| `446-11-5-riabe/` | RÈGLEMENT concernant l’intervention artistique sur les bâtiments de l’Etat (446.11.5) | 1 | current text only, in force since 1 May 2015 |
| `446-12-1-rlpmi/` | RÈGLEMENT d’application de la loi du 8 avril 2014 sur le patrimoine mobilier et immatériel (446.12.1) | 2 | each consolidated version: 1 May 2015 to 26 March 2024 |
| `446-15-1-rf-pccl/` | RÈGLEMENT concernant le Fonds pour la promotion culturelle de la Cathédrale de Lausanne (446.15.1) | 2 | each consolidated version: 26 August 2002 to 1 March 2023 |
| `449-12-1-rdsdm/` | RÈGLEMENT d'application du décret du 9 mars 2021 instituant des mesures de soutien à la diversité des médias (449.12.1) | 1 | current text only, in force since 1 February 2024 |
| `450-11-1-rlprpnp/` | RÈGLEMENT d'application de la loi du 30 août 2022 sur la protection du patrimoine naturel et paysager (450.11.1) | 2 | each consolidated version: 1 July 2024 to 1 January 2025 |
| `451-16-1-rlprpci/` | RÈGLEMENT sur la protection du patrimoine culturel immobilier (451.16.1) | 1 | current text only, in force since 1 June 2022 |
| `810-41-1-rccg/` | RÈGLEMENT sur les centres de consultation en matière de grossesse (810.41.1) | 1 | current text only, in force since 9 January 1991 |
| `811-41-1-rlabv/` | RÈGLEMENT sur les laboratoires d'analyses vétérinaires et sur les cliniques vétérinaires (811.41.1) | 1 | current text only, in force since 29 April 1987 |
| `818-41-1-rdspf/` | RÈGLEMENT sur les décès, les sépultures et les pompes funèbres (818.41.1) | 2 | each consolidated version: 1 October 2012 to 1 January 2018 |
| `831-41-2-ro-rp/` | RÈGLEMENT d'organisation des Retraites Populaires (831.41.2) | 3 | each consolidated version: 1 January 1990 to 1 December 2015 |
| `850-41-1-rlpromin/` | RÈGLEMENT d'application de la loi du 4 mai 2004 sur la protection des mineurs (850.41.1) | 1 | current text only, in force since 1 March 2017 |
| `850-41-5-rf-pj/` | RÈGLEMENT sur le Fonds pour la protection de la jeunesse et en faveur de l'enfance malheureuse et abandonnée (850.41.5) | 3 | each consolidated version: 1 May 2012 to 1 May 2018 |
| `850-42-1-rf-em/` | RÈGLEMENT sur le fonds d'encouragement des mineurs (850.42.1) | 1 | current text only, in force since 3 March 1999 |
| `916-41-1-rlvlfe/` | RÈGLEMENT d'exécution de la loi d'application de la législation fédérale sur les épizooties (916.41.1) | 2 | each consolidated version: 1 January 1992 to 1 January 2016 |
| `916-41-2-riehc/` | RÈGLEMENT sur les équipes d'intervention en cas d'épizootie hautement contagieuse (916.41.2) | 1 | current text only, in force since 1 January 2024 |
| `916-41-3-ri-vet/` | RÈGLEMENT fixant le tarif des indemnités versées aux médecins-vétérinaires pour la lutte contre les épizooties et d'autres missions officielles (916.41.3) | 1 | current text only, in force since 1 January 2024 |
| `916-41-5-ri-etax/` | RÈGLEMENT fixant le tarif des indemnités dues aux experts taxateurs (916.41.5) | 1 | current text only, in force since 1 October 2022 |
| `963-41-1-rlaien/` | RÈGLEMENT d'application de la loi du 17 novembre 1952 concernant l'assurance des bâtiments et du mobilier contre l'incendie et les éléments naturels (963.41.1) | 4 | each consolidated version: 1 January 2000 to 1 March 2019 |
| `963-41-2-rpfsdis/` | RÈGLEMENT sur la participation aux frais du service de défense contre l’incendie et de secours (963.41.2) | 2 | each consolidated version: 1 January 2014 to 6 September 2023 |
| `963-41-4-rfstt/` | RÈGLEMENT sur le Fonds de secours en cas de tremblements de terre (963.41.4) | 1 | current text only, in force since 1 January 1989 |
| `963-41-5-rpfpien/` | RÈGLEMENT sur la participation aux frais de prévention contre l'incendie et les éléments naturels (963.41.5) | 2 | each consolidated version: 1 January 2014 to 1 January 2026 |
| `503-11-1-rtirs/` | RÈGLEMENT sur les tirs (503.11.1) | 1 | current text only, in force since 1 November 2013 |
| `510-21-1-rorca/` | RÈGLEMENT sur l'organisation et la coordination des secours en cas d'accident majeur ou de catastrophe (510.21.1) | 2 | each consolidated version: 1 July 2006 to 1 November 2015 |
| `510-21-5-rssan/` | RÈGLEMENT sur le service sanitaire en cas de situation particulière, d'accident majeur ou de catastrophe (510.21.5) | 1 | current text only, in force since 1 July 2008 |
| `510-62-1-rlgeo-vd/` | RÈGLEMENT d'application de la loi du 8 mai 2012 sur la géoinformation (510.62.1) | 5 | each consolidated version: 1 January 2013 to 1 June 2023 |
| `520-11-1-roapci/` | RÈGLEMENT sur l'organisation et l'administration de la protection civile vaudoise (520.11.1) | 1 | current text only, in force since 1 January 2019 |
| `520-21-1-rop/` | RÈGLEMENT sur les ouvrages de protection (520.21.1) | 1 | current text only, in force since 1 July 2019 |
| `520-21-2-riipci/` | RÈGLEMENT sur les interventions et l'instruction de la protection civile vaudoise (520.21.2) | 1 | current text only, in force since 1 January 2019 |
| `818-55-1-ri-ddc/` | RÈGLEMENT fixant le tarif des indemnités dues pour l'équarrissage des animaux, l'enfouissement et la destruction des déchets carnés (818.55.1) | 1 | current text only, in force since 1 January 1991 |
| `935-51-1-rjpe/` | RÈGLEMENT sur les jeux de petite envergure (935.51.1) | 2 | each consolidated version: 1 January 2021 to 1 June 2024 |
| `935-51-3-rpoker/` | RÈGLEMENT sur l’organisation de tournois de poker qualifiés comme jeux d’adresse (935.51.3) | 1 | current text only, in force since 1 October 2008 |
| `935-53-2-rbge/` | RÈGLEMENT sur la répartition du bénéfice net résiduel des loteries et paris sportifs de grande envergure (935.53.2) | 3 | each consolidated version: 1 January 2021 to 1 November 2024 |
| `610-15-1-rlsubv/` | RÈGLEMENT d'application de la loi du 22 février 2005 sur les subventions (610.15.1) | 4 | each consolidated version: 1 January 2007 to 1 January 2020 |
| `614-05-1-rccomptes/` | RÈGLEMENT de la Cour des comptes (614.05.1) | 2 | each consolidated version: 1 February 2016 to 1 January 2023 |
| `614-11-1-rlccf/` | RÈGLEMENT d’application de la loi du 12 mars 2013 sur le Contrôle cantonal des finances (614.11.1) | 2 | each consolidated version: 1 December 2017 to 1 June 2023 |
| `641-11-1-ris/` | RÈGLEMENT sur l'imposition à la source (641.11.1) | 2 | each consolidated version: 1 January 2021 to 1 January 2026 |
| `642-11-1-rili/` | RÈGLEMENT relatif à l'imposition d'après la dépense prévue par l'article 15 de la loi du 4 juillet 2000 sur les impôts directs cantonaux (642.11.1) | 3 | each consolidated version: 1 January 2001 to 1 January 2016 |
| `642-11-2-rdfip/` | RÈGLEMENT sur la déduction des frais relatifs aux immeubles privés (642.11.2) | 1 | current text only, in force since 1 January 2020 |
| `642-11-3-rifam/` | RÈGLEMENT sur l’imposition de la famille (642.11.3) | 5 | each consolidated version: 1 January 2011 to 1 January 2024 |
| `642-11-3-0-rifam/` | RÈGLEMENT remplaçant provisoirement le règlement du 11 décembre 2000 sur l'imposition de la famille (642.11.3.0) | 3 | each consolidated version: 1 January 2006 to 1 January 2009 |
| `642-11-4-rdace/` | RÈGLEMENT sur la déduction en matière d'assurances et d'intérêts de capitaux d'épargne (642.11.4) | 1 | current text only, in force since 1 January 2001 |
| `642-11-5-rbispm/` | RÈGLEMENT sur le passage de la taxation bisannuelle praenumerando à la taxation annuelle postnumerando des personnes morales (642.11.5) | 1 | current text only, in force since 1 January 1995 |
| `642-11-6-rperc/` | RÈGLEMENT concernant la perception des contributions (642.11.6) | 23 | each consolidated version: 1 January 2005 to 1 January 2026 |
| `642-11-7-rpepp/` | RÈGLEMENT relatif à la perception échelonnée des impôts des personnes physiques (642.11.7) | 3 | each consolidated version: 1 January 2007 to 1 January 2013 |
| `642-11-8-rpepm/` | RÈGLEMENT relatif à la perception échelonnée des impôts des personnes morales (642.11.8) | 3 | each consolidated version: 1 January 2003 to 1 January 2016 |
| `642-11-9-1-rvloc/` | RÈGLEMENT sur la détermination de la valeur locative (642.11.9.1) | 23 | each consolidated version: 1 January 2004 to 1 January 2026 |
| `642-11-9-5-ricisf/` | RÈGLEMENT sur l'imposition complémentaire des immeubles appartenant aux sociétés et fondations (642.11.9.5) | 2 | each consolidated version: 1 January 2003 to 1 January 2010 |
| `642-11-9-6-rlsi/` | RÈGLEMENT relatif à la liquidation des sociétés immobilières (642.11.9.6) | 1 | current text only, in force since 1 January 2001 |
| `642-11-9-7-rdve/` | RÈGLEMENT sur le dépôt de la déclaration d'impôt des personnes physiques et des personnes morales, en particulier par voie électronique (642.11.9.7) | 6 | each consolidated version: 1 January 2017 to 1 January 2024 |
| `642-11-9-8-rted/` | RÈGLEMENT sur la transmission électronique de documents par l'autorité fiscale aux contribuables (642.11.9.8) | 1 | current text only, in force since 1 January 2024 |
| `642-21-1-rlefi/` | RÈGLEMENT sur l'estimation fiscale des immeubles (642.21.1) | 1 | current text only, in force since 25 January 1991 |
| `642-22-1-retif/` | RÈGLEMENT sur l'estimation des titres non cotés et des titres non régulièrement cotés en bourse ou hors bourse pour l'impôt sur la fortune (642.22.1) | 2 | each consolidated version: 1 January 2022 to 1 June 2022 |
| `648-21-1-rldsd/` | RÈGLEMENT d'application de la loi du 27 septembre 2005 sur la dation en paiement d'impôts sur les successions et donations (648.21.1) | 1 | current text only, in force since 1 May 2010 |
| `652-31-1-ricc/` | RÈGLEMENT concernant la perception de l'impôt cantonal sur les chiens (652.31.1) | 5 | each consolidated version: 1 January 2005 to 1 January 2021 |
| `850-61-1-rlaih/` | RÈGLEMENT d'application de la loi du 10 février 2004 sur les mesures d'aide et d'intégration des personnes handicapées (850.61.1) | 5 | each consolidated version: 1 January 2015 to 1 January 2024 |
| `935-61-1-rlccr/` | RÈGLEMENT d'application de la loi du 11 septembre 1978 sur les campings et caravanings résidentiels (935.61.1) | 1 | current text only, in force since 23 April 1980 |
| `700-11-1-rlatc/` | RÈGLEMENT d'application de la loi du 4 décembre 1985 sur l'aménagement du territoire et les constructions (700.11.1) | 13 | each consolidated version: 14 May 2001 to 1 January 2026 |
| `700-11-2-rlat/` | RÈGLEMENT sur l’aménagement du territoire (700.11.2) | 3 | each consolidated version: 1 September 2018 to 1 October 2020 |
| `721-01-1-rlpdp/` | RÈGLEMENT sur la police des eaux dépendant du domaine public (721.01.1) | 1 | current text only, in force since 1 January 2004 |
| `721-09-1-rlml/` | RÈGLEMENT d'application de la loi du 10 mai 1926 sur le marchepied le long des lacs et sur les plans riverains (721.09.1) | 1 | current text only, in force since 23 September 2002 |
| `721-31-1-rapd/` | RÈGLEMENT sur l'approbation des plans directeurs et des installations de distribution d'eau et sur l'approvisionnement en eau potable en temps de crise (721.31.1) | 1 | current text only, in force since 25 February 1998 |
| `725-01-1-rlrou/` | RÈGLEMENT d'application de la loi du 10 décembre 1991 sur les routes (725.01.1) | 3 | each consolidated version: 19 January 1994 to 1 May 2007 |
| `725-01-2-rcrc/` | RÈGLEMENT sur la classification des routes cantonales (725.01.2) | 2 | each consolidated version: 1 June 2012 to 1 September 2017 |
| `725-01-3-rhrc/` | RÈGLEMENT sur la hiérarchie des routes cantonales (725.01.3) | 2 | each consolidated version: 1 January 2012 to 1 September 2017 |
| `726-01-1-rlmp-vd/` | RÈGLEMENT d'application de la loi du 14 juin 2022 sur les marchés publics (726.01.1) | 2 | each consolidated version: 1 January 2023 to 1 July 2024 |
| `730-01-1-rlvlene/` | RÈGLEMENT d'application de la loi du 16 mai 2006 sur l'énergie (730.01.1) | 8 | each consolidated version: 1 November 2006 to 1 January 2026 |
| `730-01-4-r-cecb/` | RÈGLEMENT sur le certificat énergétique cantonal des bâtiments (730.01.4) | 2 | each consolidated version: 1 January 2017 to 1 January 2023 |
| `730-01-5-rf-ene/` | RÈGLEMENT sur le Fonds pour l'énergie (730.01.5) | 4 | each consolidated version: 1 November 2006 to 1 January 2021 |
| `730-02-1-rlrnss/` | RÈGLEMENT d'application de la loi du 11 décembre 2018 sur les ressources naturelles du sous-sol (730.02.1) | 1 | current text only, in force since 1 January 2020 |
| `730-05-1-rpcl/` | RÈGLEMENT sur l'utilisation des pompes à chaleur (730.05.1) | 1 | current text only, in force since 1 September 2011 |
| `730-11-1-rzdel/` | RÈGLEMENT sur les zones de desserte et les concessions de distribution d'électricité (730.11.1) | 1 | current text only, in force since 1 April 2019 |
| `730-115-5-rcsecel/` | RÈGLEMENT sur la Commission cantonale de surveillance du secteur électrique (730.115.5) | 1 | current text only, in force since 1 October 2009 |
| `730-115-6-re-dfel/` | RÈGLEMENT sur l'émolument cantonal lié à la distribution d'électricité (730.115.6) | 2 | each consolidated version: 1 October 2009 to 1 January 2026 |
| `730-115-7-ri-dfel/` | RÈGLEMENT sur l'indemnité communale liée à l'usage du sol pour la distribution d'électricité (730.115.7) | 1 | current text only, in force since 1 October 2009 |
| `730-40-5-rpcg/` | RÈGLEMENT sur la procédure applicable aux conduites de gaz de 0 à 5 bar (730.40.5) | 1 | current text only, in force since 1 November 2006 |
| `731-01-1-rllc/` | RÈGLEMENT d'application de la loi du 5 septembre 1944 sur l'utilisation des lacs et cours d'eau dépendant du domaine public et de la loi du 12 mai 1948 réglant l'occupation et l'exploitation des eaux souterraines dépendant du domaine public cantonal (731.01.1) | 3 | each consolidated version: 23 September 2002 to 1 January 2010 |
| `731-01-1-3-rpbeel/` | RÈGLEMENT sur la participation de l'Etat aux bénéfices des entreprises électriques sous forme d'un versement proportionnel à l'énergie électrique produite (731.01.1.3) | 1 | current text only, in force since 1 January 1993 |
| `740-21-1-rrtpu/` | RÈGLEMENT sur la répartition entre communes des contributions accordées aux transports publics (740.21.1) | 1 | current text only, in force since 23 September 2002 |
| `740-22-1-rstfm/` | RÈGLEMENT sur les subventions d'investissement en faveur du transport ferroviaire de marchandises (740.22.1) | 1 | current text only, in force since 1 March 2026 |
| `740-24-risa/` | RÈGLEMENT concernant l'interdiction de survol de périmètres déterminés par des aéronefs sans occupants de poids inférieur à 30kg (740.24) | 1 | current text only, in force since 15 July 2019 |
| `740-25-rttp/` | RÈGLEMENT sur le transport de personnes à titre professionnel (740.25) | 2 | each consolidated version: 1 January 2020 to 1 January 2025 |
| `741-01-1-rlvcr/` | RÈGLEMENT d'application de la loi vaudoise sur la circulation routière (741.01.1) | 5 | each consolidated version: 28 September 1994 to 1 January 2013 |
| `741-01-2-rvsr/` | RÈGLEMENT sur la signalisation routière (741.01.2) | 1 | current text only, in force since 1 July 1991 |
| `741-11-1-rtvb/` | RÈGLEMENT d'application de la loi du 21 mars 2023 sur la taxe des véhicules automobiles et des bateaux (741.11.1) | 2 | each consolidated version: 1 January 2024 to 1 January 2026 |
| `741-15-1-re-san/` | RÈGLEMENT sur les émoluments perçus par le Service des automobiles et de la navigation (741.15.1) | 7 | each consolidated version: 1 January 2017 to 1 September 2026 |
| `741-17-1-rrpl/` | RÈGLEMENT pour la perception des redevances fédérales sur le trafic des poids lourds et l'utilisation des routes nationales (741.17.1) | 1 | current text only, in force since 24 October 1984 |
| `743-01-1-re-tsm/` | RÈGLEMENT fixant les émoluments concernant les installations de transport par câbles, skilifts et autres monte-pentes sans concession fédérale (743.01.1) | 1 | current text only, in force since 1 January 2006 |
| `743-91-1-reglement-citt/` | RÈGLEMENT sur la construction et l’exploitation des téléphériques et téléskis sans concession fédérale (743.91.1) | 1 | current text only, in force since 2 June 2022 |
| `747-23-5-rkite/` | RÈGLEMENT concernant la navigation au moyen de planches tirées par des cerfs-volants (kitesurf) (747.23.5) | 1 | current text only, in force since 1 March 2016 |
| `800-01-5-rf-dps/` | RÈGLEMENT sur le fonds pour le développement de la prévention et de la promotion de la santé (800.01.5) | 2 | each consolidated version: 1 July 2009 to 1 May 2018 |
| `800-02-1-rliflp/` | RÈGLEMENT d'application de la loi du 23 juin 2009 sur l'interdiction de fumer dans les lieux publics (800.02.1) | 3 | each consolidated version: 15 September 2009 to 1 October 2010 |
| `801-11-1-rlavasad/` | RÈGLEMENT d'application de la loi du 6 octobre 2009 sur l'Association vaudoise d'aide et de soins à domicile (801.11.1) | 2 | each consolidated version: 1 January 2010 to 1 July 2017 |
| `801-15-1-rosad/` | RÈGLEMENT sur les organisations d'aide et de soins à domicile (801.15.1) | 1 | current text only, in force since 1 July 2021 |
| `810-01-3-rclpfes/` | RÈGLEMENT précisant les conditions à remplir par les établissements sanitaires privés pour être reconnus d'intérêt public au sens de la loi du 5 décembre 1978 sur la planification et le financement des établissements sanitaires d'intérêt public (810.01.3) | 6 | each consolidated version: 1 January 2010 to 1 January 2024 |
| `810-01-5-rieh/` | RÈGLEMENT sur les investissements des établissements hospitaliers figurant sur la liste vaudoise (810.01.5) | 1 | current text only, in force since 1 January 2012 |
| `810-01-6-rctrlamal/` | RÈGLEMENT sur les conditions de travail applicables au personnel exerçant dans des établissements sanitaires reconnus d'intérêt public (810.01.6) | 2 | each consolidated version: 1 October 2013 to 1 January 2022 |
| `810-03-1-res/` | RÈGLEMENT sur les établissements sanitaires et les établissements apparentés de droit privé dans le Canton de Vaud (810.03.1) | 4 | each consolidated version: 1 January 2011 to 1 October 2025 |
| `810-05-1/` | RÈGLEMENT fixant les normes relatives à la comptabilité, au système d’information, à la révision du reporting annuel et au système de contrôle interne des hôpitaux reconnus d’intérêt public (810.05.1) | 2 | each consolidated version: 1 January 2019 to 1 January 2025 |
| `810-11-1-rlhc/` | RÈGLEMENT d’application de la loi du 16 novembre 1993 sur les Hospices cantonaux (810.11.1) | 6 | each consolidated version: 1 June 2009 to 1 January 2024 |
| `810-211-1-rdpmu/` | RÈGLEMENT d'application du décret du 13 mai 1957 sur la Policlinique médicale universitaire et dispensaire central de Lausanne (810.211.1) | 3 | each consolidated version: 1 May 2019 to 1 October 2026 |
| `810-31-1-rccms/` | RÈGLEMENT fixant les normes relatives à la comptabilité, au contrôle des comptes et à l’analyse des établissements médico-sociaux, des lits de type C des hôpitaux et des centres de traitement et de réadaptation, reconnus d’intérêt public, ainsi que des homes non médicalisés (810.31.1) | 4 | each consolidated version: 1 July 2008 to 1 June 2026 |
| `810-31-5-rciemms/` | RÈGLEMENT sur la participation de l’Etat aux charges d’investissement immobilières ainsi que sur l’intégration des charges d'entretien et mobilières aux tarifs des établissements médico-sociaux reconnus d'intérêt public (810.31.5) | 1 | current text only, in force since 2 March 2018 |
| `810-321-1-ro-acb/` | RÈGLEMENT organisant l'Asile Cottier-Boys (810.321.1) | 1 | current text only, in force since 1 January 1940 |
| `810-322-1-ro-fmd/` | RÈGLEMENT organisant l'Asile Cottier-Boys, section «Major Davel» (810.322.1) | 1 | current text only, in force since 1 January 1940 |
| `810-81-1-ruph/` | RÈGLEMENT sur les urgences préhospitalières et le transport des patients (810.81.1) | 1 | current text only, in force since 1 May 2018 |
| `810-94-1-rc-hirc/` | RÈGLEMENT d’application de la Convention intercantonale du 17 décembre 2008 sur l’Hôpital Riviera-Chablais, Vaud-Valais, relatif à l’exploitation de l’établissement (810.94.1) | 2 | each consolidated version: 2 November 2016 to 1 October 2025 |
| `810-95-1-rc-hib/` | RÈGLEMENT d'application de la Convention intercantonale du 21 août 2013 sur l'Hôpital intercantonal de la Broye (HIB) Vaud-Fribourg, relatif à l'exploitation de l'établissement (810.95.1) | 1 | current text only, in force since 6 October 2025 |
| `811-01-1-reps/` | RÈGLEMENT sur l'exercice des professions de la santé (811.01.1) | 3 | each consolidated version: 1 January 2011 to 16 December 2020 |
| `811-03-1-rmecop/` | RÈGLEMENT sur le Bureau cantonal de la médiation et la Commission d'examen des plaintes des patients et des résidents (811.03.1) | 1 | current text only, in force since 1 January 2015 |
| `811-05-1-rcsfs/` | RÈGLEMENT instituant une commission spécialisée pour le classement des fonctions sanitaires (811.05.1) | 1 | current text only, in force since 22 February 1995 |
| `811-12-1-rinvestpro/` | RÈGLEMENT sur le fonds du programme cantonal de lutte contre la pénurie de personnel dans le domaine de la santé et des soins infirmiers (811.12.1) | 1 | current text only, in force since 1 July 2025 |
| `811-13-1-r-med/` | RÈGLEMENT sur les médecins chefs de département, les médecins chefs de service, les médecins cadres, les médecins agréés et les médecins hospitaliers du CHUV (811.13.1) | 1 | current text only, in force since 1 January 2017 |
| `812-05-1-rlabh/` | RÈGLEMENT concernant les laboratoires d'analyses pour la médecine humaine (812.05.1) | 1 | current text only, in force since 5 March 1986 |
| `812-07-1-rrmedv/` | RÈGLEMENT sur la remise des médicaments vétérinaires (812.07.1) | 1 | current text only, in force since 1 June 2010 |
| `813-11-1-rvlchim/` | RÈGLEMENT d'application de la loi fédérale du 15 décembre 2000 sur les produits chimiques (813.11.1) | 2 | each consolidated version: 1 January 2008 to 1 January 2016 |
| `814-01-1-rvlpe/` | RÈGLEMENT d'application de la loi fédérale du 7 octobre 1983 sur la protection de l'environnement (814.01.1) | 2 | each consolidated version: 1 January 1994 to 1 January 2016 |
| `814-01-1-1-rcdc/` | RÈGLEMENT sur le contrôle obligatoire des installations de distribution de carburant (814.01.1.1) | 1 | current text only, in force since 1 January 2023 |
| `814-03-1-rvoeie/` | RÈGLEMENT d'application de l'ordonnance fédérale relative à l'étude de l'impact sur l'environnement (814.03.1) | 2 | each consolidated version: 1 May 1990 to 1 March 2008 |
| `814-05-1-rcocc/` | RÈGLEMENT sur le contrôle obligatoire des installations de chauffage à combustion (814.05.1) | 5 | each consolidated version: 17 May 2002 to 1 July 2020 |
| `814-11-1-rlgd/` | RÈGLEMENT d'application de la loi du 5 septembre 2006 sur la gestion des déchets (814.11.1) | 1 | current text only, in force since 5 March 2008 |
| `814-31-1-rlpep/` | RÈGLEMENT d'application de la loi du 17 septembre 1974 sur la protection des eaux contre la pollution (814.31.1) | 2 | each consolidated version: 3 December 1993 to 1 January 2026 |
| `814-31-1-2-rieeu/` | RÈGLEMENT sur l’entretien des installations particulières d’épuration des eaux usées ménagères et des installations de prétraitement industrielles (814.31.1.2) | 2 | each consolidated version: 1 March 2009 to 1 February 2023 |
| `814-31-4-r-abc/` | RÈGLEMENT en matière d'organisation et de gestion en cas d'évènements ABC (814.31.4) | 2 | each consolidated version: 1 January 2016 to 1 January 2025 |
| `814-31-5-rslm/` | RÈGLEMENT sur les subventions en matière de lutte contre les micropolluants (814.31.5) | 1 | current text only, in force since 1 December 2016 |
| `817-11-1-re-cda/` | RÈGLEMENT fixant les émoluments perçus par les organes de contrôle des denrées alimentaires (817.11.1) | 2 | each consolidated version: 1 February 2004 to 1 January 2006 |
| `817-21-1-raacv/` | RÈGLEMENT sur l'abattage d'animaux et le contrôle des viandes (817.21.1) | 1 | current text only, in force since 1 December 2020 |
| `817-31-1-rchamp/` | RÈGLEMENT sur le commerce et le contrôle des champignons (817.31.1) | 1 | current text only, in force since 1 February 2004 |
| `818-155-1-rlct/` | RÈGLEMENT sur la lutte contre la tuberculose dans le Canton de Vaud (818.155.1) | 1 | current text only, in force since 22 May 1996 |
| `818-21-1-rlca/` | RÈGLEMENT sur la lutte contre l'alcoolisme (818.21.1) | 1 | current text only, in force since 20 August 1986 |
| `818-21-2-rf-addic/` | RÈGLEMENT sur le fonds pour la prévention et la lutte contre les addictions et le fonds de la dîme de l'alcool (818.21.2) | 3 | each consolidated version: 1 July 2009 to 1 January 2026 |
| `818-21-4-rgea/` | RÈGLEMENT sur le Groupe d'experts en matière d'addictions (818.21.4) | 1 | current text only, in force since 1 July 2009 |
| `818-21-5-rcaddic/` | RÈGLEMENT sur la Commission de promotion de la santé et de lutte contre les addictions (818.21.5) | 1 | current text only, in force since 1 July 2009 |
| `818-31-1-rqhep/` | RÈGLEMENT sur le contrôle de la qualité hygiénique de l'eau des plages (818.31.1) | 1 | current text only, in force since 26 June 1987 |
| `819-31-1-rpac/` | RÈGLEMENT de prévention des accidents dus aux chantiers (819.31.1) | 2 | each consolidated version: 1 June 2003 to 1 April 2019 |
| `821-01-1-rlprcc/` | RÈGLEMENT d'application de la loi du 28 octobre 2003 sur la prévention et le règlement des conflits collectifs (821.01.1) | 1 | current text only, in force since 1 January 2008 |
| `822-01-1-rlpe/` | RÈGLEMENT sur le logement du personnel par les employeurs (822.01.1) | 2 | each consolidated version: 1 July 2002 to 1 January 2006 |
| `822-05-1-rabc/` | RÈGLEMENT concernant la construction, l'aménagement et l'exploitation des baraques de chantiers (822.05.1) | 1 | current text only, in force since 1 July 1991 |
| `822-11-1-rlemp/` | RÈGLEMENT d'application de la loi du 5 juillet 2005 sur l'emploi (822.11.1) | 15 | each consolidated version: 1 January 2006 to 1 April 2024 |
| `831-01-1-rloai/` | RÈGLEMENT d'application de la loi du 14 septembre 1993 instituant l'office de l'assurance-invalidité pour le Canton de Vaud (831.01.1) | 1 | current text only, in force since 1 January 1995 |
| `831-11-1-rlccp/` | RÈGLEMENT d'application de la loi du 26 mai 1965 sur l'organisation de la Caisse cantonale de compensation (831.11.1) | 1 | current text only, in force since 1 August 1984 |
| `831-15-1-raas/` | RÈGLEMENT sur les agences d'assurances sociales (831.15.1) | 2 | each consolidated version: 1 February 2004 to 1 January 2025 |
| `831-21-1-rlvpc-rfm/` | RÈGLEMENT d'application de la loi du 13 novembre 2007 sur les prestations complémentaires à l'assurance vieillesse, survivants et invalidité et sur le remboursement des frais de maladie et d'invalidité en matière de prestations complémentaires (831.21.1) | 4 | each consolidated version: 31 December 2019 to 1 November 2025 |
| `832-01-1-rlvlamal/` | RÈGLEMENT concernant la loi du 25 juin 1996 d'application vaudoise de la loi fédérale sur l'assurance-maladie (832.01.1) | 10 | each consolidated version: 1 January 2002 to 1 January 2027 |
| `832-81-1-rvlaa/` | RÈGLEMENT d'introduction de la loi fédérale du 20 mars 1981 sur l'assurance-accidents (832.81.1) | 1 | current text only, in force since 1 January 1984 |
| `836-01-1-rlvlafam/` | RÈGLEMENT concernant la loi d’application de la loi fédérale sur les allocations familiales et sur des prestations cantonales en faveur de la famille (836.01.1) | 4 | each consolidated version: 1 January 2009 to 1 March 2019 |
| `836-15-1-rcavs/` | RÈGLEMENT concernant les tâches supplémentaires de la Caisse cantonale AVS, relatives à la Caisse générale d'allocations familiales en faveur des employés, ouvriers et fonctionnaires et à la Fédération rurale vaudoise de mutualité et d'assurances sociales, ainsi qu'au régime fédéral des allocations familiales aux travailleurs agricoles et aux petits paysans (836.15.1) | 1 | current text only, in force since 1 July 1962 |
| `840-11-1-rll/` | RÈGLEMENT d'application de la loi sur le logement du 9 septembre 1975 (840.11.1) | 7 | each consolidated version: 1 March 2007 to 19 March 2025 |
| `840-11-2-rcol/` | RÈGLEMENT sur les conditions d'occupation des logements construits ou rénovés avec l'appui financier des pouvoirs publics (840.11.2) | 5 | each consolidated version: 24 July 1991 to 1 January 2026 |
| `840-11-2-5-rcollm/` | RÈGLEMENT sur les conditions d'occupation des logements à loyers modérés (840.11.2.5) | 5 | each consolidated version: 1 March 2007 to 19 March 2025 |
| `840-11-3-rail/` | RÈGLEMENT sur l'aide individuelle au logement (840.11.3) | 3 | each consolidated version: 1 January 2008 to 1 January 2013 |
| `840-11-5-rpclo/` | RÈGLEMENT sur les prêts et les cautionnements pour les logements (840.11.5) | 2 | each consolidated version: 1 January 2020 to 13 November 2020 |
| `840-11-6-rafcvch/` | RÈGLEMENT sur l'aide financière accordée à la Coopérative vaudoise de cautionnement hypothécaire favorisant l'accession à la propriété du logement (840.11.6) | 2 | each consolidated version: 1 January 2008 to 28 June 2023 |
| `840-15-1-rlpppl/` | RÈGLEMENT d'application de la loi du 10 mai 2016 sur la préservation et la promotion du parc locatif (840.15.1) | 4 | each consolidated version: 1 January 2018 to 1 November 2023 |
| `850-01-1-rlof/` | RÈGLEMENT d'application de la loi sur l'organisation et le financement de la politique sociale (850.01.1) | 5 | each consolidated version: 1 January 2005 to 1 January 2025 |
| `850-03-1-rlhps/` | RÈGLEMENT d’application de la loi du 9 novembre 2010 sur l’harmonisation et la coordination de l’octroi des prestations sociales et d’aide à la formation et au logement cantonales vaudoises (850.03.1) | 13 | each consolidated version: 1 January 2013 to 1 January 2027 |
| `850-051-1-rlasv/` | RÈGLEMENT d'application de la loi du 2 décembre 2003 sur l'action sociale vaudoise (850.051.1) | 11 | each consolidated version: 1 January 2006 to 1 March 2026 |
| `850-051-3-rflp/` | RÈGLEMENT instituant un Fonds de lutte contre la précarité (850.051.3) | 1 | current text only, in force since 1 January 2019 |
| `850-051-4-rf-cossy/` | RÈGLEMENT concernant le Fonds Cossy (850.051.4) | 1 | current text only, in force since 1 July 2026 |
| `850-053-1-rlpcfam/` | RÈGLEMENT d'application de la loi du 23 novembre 2010 sur les prestations complémentaires cantonales pour familles et les prestations cantonales de la rente-pont (850.053.1) | 11 | each consolidated version: 1 October 2011 to 1 January 2027 |
| `850-11-1-rlaprams/` | RÈGLEMENT d'application de la loi du 24 janvier 2006 d'aide aux personnes recourant à l'action médico-sociale (850.11.1) | 10 | each consolidated version: 1 May 2006 to 1 July 2026 |
| `850-36-1-rlrapa/` | RÈGLEMENT d'application de la loi du 10 février 2004 sur le recouvrement et les avances sur pensions alimentaires (850.36.1) | 1 | current text only, in force since 1 July 2024 |
| `900-05-1-rladepr/` | RÈGLEMENT d’application de la loi du 12 juin 2007 sur l’appui au développement économique pour les subventions aux projets régionaux (900.05.1) | 2 | each consolidated version: 1 January 2017 to 1 July 2023 |
| `900-05-2-rladepe/` | RÈGLEMENT d’application de la loi du 12 juin 2007 sur l’appui au développement économique pour les aides indirectes pour les prestations de services et les subventions aux projets d’entreprises (900.05.2) | 1 | current text only, in force since 1 January 2017 |
| `900-051-1-rfiv/` | RÈGLEMENT sur l'emploi du fonds de soutien à l'industrie vaudoise (900.051.1) | 2 | each consolidated version: 1 January 2025 to 12 February 2025 |
| `900-056-1-rf-inno/` | RÈGLEMENT sur le fonds de soutien à l'innovation (900.056.1) | 2 | each consolidated version: 1 May 2021 to 3 June 2026 |
| `900-057-1-rfed/` | RÈGLEMENT sur le fonds de soutien à l'économie durable (900.057.1) | 2 | each consolidated version: 22 December 2021 to 1 January 2025 |
| `910-03-1-rlvlagr/` | RÈGLEMENT d'application de la loi sur l'agriculture vaudoise (910.03.1) | 1 | current text only, in force since 1 January 2011 |
| `910-11-1-rpeagr/` | RÈGLEMENT sur la promotion de l'économie agricole (910.11.1) | 6 | each consolidated version: 1 January 2011 to 1 May 2021 |
| `910-11-5-rsfpv/` | RÈGLEMENT fixant des conditions à l’octroi de soutiens financiers à la production porcine vaudoise (910.11.5) | 1 | current text only, in force since 1 July 2018 |
| `910-11-6-rsfpld/` | RÈGLEMENT fixant les conditions à l'octroi d'un soutien financier cantonal à une production laitière différenciée (910.11.6) | 2 | each consolidated version: 1 July 2020 to 1 November 2022 |
| `910-21-1-ragreco/` | RÈGLEMENT sur l'agroécologie (910.21.1) | 2 | each consolidated version: 1 January 2011 to 11 June 2025 |
| `913-11-1-rlaf/` | RÈGLEMENT d'application de la loi du 29 novembre 1961 sur les améliorations foncières (913.11.1) | 4 | each consolidated version: 1 December 1999 to 25 June 2010 |
| `913-11-2-rmfaf/` | RÈGLEMENT fixant les mesures financières en faveur des améliorations foncières (913.11.2) | 1 | current text only, in force since 1 January 2024 |
| `914-01-3-rcagr/` | RÈGLEMENT sur le crédit agricole (914.01.3) | 3 | each consolidated version: 1 January 2011 to 22 April 2026 |
| `916-131-1-rpv/` | RÈGLEMENT sur la protection des végétaux (916.131.1) | 1 | current text only, in force since 1 January 2011 |
| `916-38-1-ri-ir/` | RÈGLEMENT fixant le tarif des indemnités dues aux inspecteurs des ruchers (916.38.1) | 2 | each consolidated version: 1 May 2005 to 1 January 2022 |
| `921-01-1-rlvlfo/` | RÈGLEMENT d'application de la loi forestière du 8 mai 2012 (921.01.1) | 2 | each consolidated version: 1 January 2014 to 15 November 2021 |
| `922-03-1-rlfaune/` | RÈGLEMENT d'exécution de la loi du 28 février 1989 sur la faune (922.03.1) | 8 | each consolidated version: 7 July 2004 to 1 January 2026 |
| `922-05-1-1-rsfa/` | RÈGLEMENT sur le séquestre et la mise en fourrière d'animaux (922.05.1.1) | 2 | each consolidated version: 14 May 1997 to 1 August 2004 |
| `923-01-1-rlpeche/` | RÈGLEMENT d'application de la loi du 29 novembre 1978 sur la pêche (923.01.1) | 4 | each consolidated version: 1 January 2008 to 1 June 2024 |
| `923-93-1-ra-peche-l/` | RÈGLEMENT d’application de l’Accord entre le Conseil fédéral suisse et le Gouvernement de la République française concernant la pêche dans le lac Léman (923.93.1) | 1 | current text only, in force since 1 January 2016 |
| `923-95-1-rc-peche-l/` | RÈGLEMENT d'exécution du concordat intercantonal du 7 octobre 1999 sur la pêche dans le lac Léman (923.95.1) | 1 | current text only, in force since 1 January 2001 |
| `923-97-1-rc-peche-morat/` | RÈGLEMENT d'exécution du concordat sur la pêche dans le lac de Morat en 2025, 2026 et 2027 (923.97.1) | 1 | current text only, in force since 1 January 2025 |
| `923-99-1-rc-peche-ne/` | RÈGLEMENT d’exécution du concordat sur la pêche dans le lac de Neuchâtel en 2025, 2026 et 2027 (923.99.1) | 1 | current text only, in force since 1 January 2025 |
| `930-01-1-rleae/` | RÈGLEMENT d'application de la loi du 31 mai 2005 sur l'exercice des activités économiques (930.01.1) | 4 | each consolidated version: 1 November 2014 to 15 July 2024 |
| `930-01-3/` | RÈGLEMENT sur le Registre cantonal des entreprises (930.01.3) | 1 | current text only, in force since 1 July 2018 |
| `931-15-1-rlcar/` | RÈGLEMENT d'application de la loi du 24 mai 1988 sur les carrières (931.15.1) | 2 | each consolidated version: 1 July 2004 to 1 December 2014 |
| `935-21-2-rcs/` | RÈGLEMENT pour les colonnes de secours (935.21.2) | 1 | current text only, in force since 11 June 1971 |
| `935-25-1-rsport/` | RÈGLEMENT sur les sports de neige, de montagne et de randonnée (935.25.1) | 1 | current text only, in force since 1 November 2014 |
| `935-27-1-rlesec/` | RÈGLEMENT sur les entreprises de sécurité (935.27.1) | 1 | current text only, in force since 1 July 2004 |
| `935-31-1-rladb/` | RÈGLEMENT d'exécution de la loi du 26 mars 2002 sur les auberges et les débits de boissons (935.31.1) | 7 | each consolidated version: 1 January 2010 to 1 March 2025 |
| `935-31-2-rccal/` | RÈGLEMENT de l'examen professionnel en vue de l'obtention du certificat cantonal d'aptitudes et du diplôme pour licence (935.31.2) | 4 | each consolidated version: 1 January 2016 to 9 September 2026 |
| `935-31-3-rcadb/` | RÈGLEMENT sur la délégation des compétences aux communes en matière d'auberges et de débits de boissons et sur le registre des licences (935.31.3) | 2 | each consolidated version: 1 January 2003 to 1 January 2016 |
| `935-31-5-re-ladb/` | RÈGLEMENT sur la taxe, les émoluments et les contributions à percevoir en application de la loi du 26 mars 2002 sur les auberges et les débits de boissons (935.31.5) | 4 | each consolidated version: 1 January 2007 to 1 March 2025 |
| `941-23-1-rd-metr/` | RÈGLEMENT sur les débours perçus en matière de métrologie (941.23.1) | 1 | current text only, in force since 1 February 2025 |
| `943-05-1-rlpros/` | RÈGLEMENT d'application de la loi du 30 mars 2004 sur l'exercice de la prostitution (943.05.1) | 1 | current text only, in force since 1 July 2021 |
| `943-11-1-rlpr/` | RÈGLEMENT d'application de la loi du 6 décembre 1988 sur les procédés de réclame (943.11.1) | 5 | each consolidated version: 22 January 1997 to 1 February 2025 |
| `962-41-6-rfepden/` | RÈGLEMENT sur le Fonds d'encouragement à la prévention des dommages provoqués par les éléments naturels (962.41.6) | 2 | each consolidated version: 1 September 2019 to 1 January 2026 |
| `963-11-1-rlpien/` | RÈGLEMENT d'application de la loi du 27 mai 1970 sur la prévention des incendies et des dangers résultant des éléments naturels (963.11.1) | 1 | current text only, in force since 28 September 1990 |
| `963-11-2-rppi/` | RÈGLEMENT concernant les prescriptions sur la prévention des incendies (963.11.2) | 1 | current text only, in force since 1 January 2019 |
| `963-15-1-rlsdis/` | RÈGLEMENT d’application de la loi du 2 mars 2010 sur le service de défense contre l'incendie et de secours (963.15.1) | 2 | each consolidated version: 1 January 2011 to 1 February 2020 |
| `963-15-3-rosrsp/` | RÈGLEMENT sur l'organisation du secours routier par les sapeurs-pompiers (963.15.3) | 1 | current text only, in force since 1 October 2011 |
| `963-15-4-rpifo/` | RÈGLEMENT en matière de prévention, d'organisation et de gestion de la lutte contre les incendies de forêt (963.15.4) | 1 | current text only, in force since 1 January 2025 |

## Source

The Base législative vaudoise (BLV), published by the Etat de Vaud at <https://prestations.vd.ch/pub/blv-publication/>. For each act it gives every consolidated version with its in-force day, and the list of amending acts with the provisions each changed and when.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**.
- Each version is dated by the in-force day the BLV gives it. The adoption day of each amending act is the `Enacted:` trailer; its publication in the Feuille des avis officiels the `Published:` trailer.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5, `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the headings of titles, chapters and sections. One paragraph or list item per line. Footnote markers are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the source document, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of each commit is the amending act (decree or law) the BLV records for the changed provisions, with an e-mail address that cannot exist. Where several amending acts take effect in one version and the BLV does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the Feuille des avis officiels and the Recueil annuel. Commentary notes are not included. Only the acts listed above are included.
