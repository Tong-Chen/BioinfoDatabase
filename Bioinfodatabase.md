## 生物信息学数据库分类概览

生物与计算机的结合让生物进入大数据时代，为方便管理各种生物数据，科学家们开发了各式各样的生物数据库。了解与自己研究领域相关的数据库，并加以利用可能会使研究工作得到事半功倍的效果。在此将常用数据库按照以下分类方式大致整理了一下，也方便检索。

分类不准或有遗漏的欢迎指出，后续将不断推出更新版本。

## 目录
1.	Meta databases
2.	Model organism databases
3.	Nucleic acid databases
   3.1	DNA databases
   3.2	Gene expression databases (mostly microarray data)
   3.3	Phenotype databases
   3.4	RNA databases
4.	Amino acid / protein databases
   4.1	Protein sequence databases
   4.2	Protein structure databases
   4.3	Protein model databases
   4.4	Protein-protein and other molecular interactions
5.	Signal transduction pathway databases
6.	Metabolic pathway and protein function databases
7.	Additional databases
   7.1	Exosomal databases
   7.2	Mathematical model databases
   7.3	Taxonomic databases
   7.4	Radiologic databases
8.	Wiki-style databases
9.	Specialized databases


## Database

### 1. Meta databases

元数据库，合并不同来源的相关数据以更新的或更加方便的形式提供新的数据，通俗的讲就是数据库的数据库，代表性的数据库主要有以下几个：

1. ConsensusPathDB
   网址：http://consensuspathdb.org/
   描述：分子功能互作数据库，基于32个公共数据库，整合了人类蛋白质相互作用，遗传相互作用信号，代谢，基因调控和药物 - 靶标相互作用的信息。

2. Entrez
   网址：https://www.ncbi.nlm.nih.gov/Class/MLACourse/Modules/Entrez/complex_boolean.html
   描述：Entrez跨数据库全局查询搜索系统是一个联合搜索引擎或门户网站，允许用户在NCBI网站上搜索许多离散的健康科学数据库。

3.  Neuroscience Information Framework
   网址：https://neuinfo.org//
   描述：整合了数百种神经科学相关资源，包括实验，临床和转化神经科学数据库，知识库，地图集和遗传/基因组资源等。

4. GeneCard 
   网址：https://www.genecards.org/
   描述：自动整合125个数据库，包含基因组、转录组、蛋白组、遗传、临床和功能信息的庞大人基因组数据库。

5. Ensembl Genomes
   网址：http://ensemblgenomes.org/
   描述：该项目由EMBL运营，提供细菌、原生生物、真菌、植物和无脊椎动物后生动物的基因组数据。
   * [NGS基础 - 参考基因组和基因注释文件](http://mp.weixin.qq.com/s/2OoXy4f1t0hE8OUqsAt1kw)
   * [NGS基础 - GTF/GFF文件格式解读和转换](http://mp.weixin.qq.com/s/rZ26i19hiS5ZOqIoqkL1Wg)

6. UCSC Genome
   网址： http://genome.ucsc.edu
   描述：主要是动物基因组信息，基因组注释，基因组保守性和基因组共线性数据。
   * [UCSC XENA - 集大成者(TCGA, ICGC)](https://mp.weixin.qq.com/s/we3raL4XowZp4vQ9zPqfYQ)
   *  [UCSC基因组浏览器](http://mp.weixin.qq.com/s/b7Cppdm-vMTgZfFVC3Q1lQ)

7. Human protein atlas
   网址：http://www.proteinatlas.org/
   描述：人体**蛋白**在细胞、组织、病理条件下的表达 
   * [ICGC数据库使用](https://mp.weixin.qq.com/s/UTlEtyDITPx9ZQOpJFczBw)


### 2. Model organism databases

模式生物数据库，为深入研究模式生物提供生物数据，如：

1. Personal Genome Project
   网址：https://www.personalgenomes.org/
   描述：来自世界各地的100,00名志愿者的人类基因组计划。

2. Mouse Genome Database(MGD)
   网址：http://www.informatics.jax.org/
   描述：MGD数据库是整合了国际上实验室小鼠生物数据的资源库，提供小鼠相关的基因组、综合遗传等信息。

3. Rat Genome Database (RGD):
   网址：https://rgd.mcw.edu/
   描述：大鼠基因组数据库。

4. PomBase
   网址：https://www.pombase.org/
   描述：裂殖酵母Schizosaccharomyces pombe的知识库。

5. Saccharomyces Genome Database (SGD):
   网址：https://www.yeastgenome.org/
   描述：酵母模型生物的基因组数据库

6. TAIR
    网址 https://www.arabidopsis.org/
    描述：最全的拟南芥资源数据库。政府为我们付费购买了使用权，以至于不少人没感觉到TAIR已经收费了。

7. Legume Information System (LIS)
   网址：https://legumeinfo.org/
   描述：豆科植物的基因组数据库。

8. Wormbase:
   网址：https://wormbase.org/#012-34-5
   描述：关于线虫模式生物秀丽隐杆线虫的生物学和基因组在线生物数据库，还包含其他相关线虫的信息。

9. Xenbase:
   网址：http://www.xenbase.org/entry/
   描述：模式生物非洲爪蟾（Xenopus tropicalis）和非洲爪蟾（Xenopus laevis）的基因组数据库。

10. Zebrafish Information Network:
      网址：http://zfin.org/
      描述：斑马鱼的基因组数据库。    

11. FlyBase:
      网址：http://flybase.org/
      描述：模式生物果蝇的基因组数据库。

12. UCSC Malaria Genome Browser:
      网址：http://enacademic.com/dic.nsf/enwiki/7907997
      描述：UCSC疟疾基因组浏览器是研究疟疾（如恶性疟原虫等）基因组的生物信息学研究工具。

### 3. Nucleic acid databases

#### 3.1	DNA databases

核酸数据库分为一级数据库（Primary databases）和二级数据库（Secondary databases）

##### **3.1.1 一级核酸数据库**

下面三个数据库是核酸的主数据库，存储来自所有生物的核酸序列，接受用户提交核酸序列，每天交换更新数据以实现他们之间的最佳同步。

1. DNA Data Bank of Japan
    网址：https://www.ddbj.nig.ac.jp/index-e.html
2. EMBL (European Bioinformatics Institute)
    网址：https://www.embl.org/
3. NCBI (National Center for Biotechnology Information)
    网址：https://www.ncbi.nlm.nih.gov/
    * [生信软件系列 - NCBI使用](http://mp.weixin.qq.com/s/4a5U8GdBoNFXkykL6m2EeA)
    * [如果你经常用PubMed，那么这个插件将非常好用！](https://mp.weixin.qq.com/s/v45sZXXCMNZGzzHE1gd-gw)
    * [一文教会你查找基因的启动子、UTR、TSS等区域以及预测转录因子结合位点](https://mp.weixin.qq.com/s/vFO7uAtI6nh-zTW7RHCixA)

##### **3.1.2 二级核酸数据库**

数目很多，先列出一些，欢迎补充：

1. 23andMe's database
   网址：https://www.23andme.com/en-int/
   描述：23andMe是一家私营的个人基因组学生物技术公司 ，主要业务是基于唾液对消费者进行基因检测，并向客户提供基因检测报告。

2. OMIM (Online Mendelian Inheritance in Man):
   网址：https://omim.org/
   描述：一个管理人类基因和人类遗传疾病特征的数据库。

4. RefSeq
   网址：https://www.ncbi.nlm.nih.gov/refseq/
   描述：参考序列数据库收集了从病毒、细菌到真核生物等主要生物的核酸序列（DNA、RNA）及其蛋白质常产物。

5. 1000 Genomes Project:
   网址：http://www.internationalgenome.org/
   描述：2008年1月启动的项目，对来自不同种族群体的一千多名匿名参与者的基因组进行了分析，并将数据公布于众。

6. SNP / Disease Databases
   网址：https://www.snpedia.com/
   描述：人SNP位点对表型的影响和贡献度数据库

#### 3.2	Gene expression databases 

这些数据库收集基因组序列，注释并分析他们，以提供公共访问。主要包括：

1. ArrayExpress
   网址：https://www.ebi.ac.uk/arrayexpress/
   描述：功能基因组数据存档；存储来自EMBL的高通量功能基因组学实验的数据；展示方式很炫酷。

2. Bioinformatic Harvester
   网址：Ensembl: http://asia.ensembl.org/index.html
   描述：为人类，小鼠，其他脊椎动物和真核生物基因组提供自动注释的数据库

4. BioGPS
   网址：http://biogps.org/#goto=welcome
   描述：强大的基因和蛋白表达注释平台

6. Gene Disease Database
    基因疾病数据库，通过整理表型-基因型关系和基因-疾病机制，以及多种复合相互作用来理解复杂疾病的潜在机制。主要数据库如下：

   5.1 The Comparative Toxicogenomics Database (CTD)
          网址：http://ctdbase.org/
   5.2 The Universal Protein Resource (UNIPROT)
         网址：https://www.uniprot.org
   5.3 The Online Mendelian Inheritance in Man
        网址：https://www.ncbi.nlm.nih.gov/omim
   5.5 The Ensembl genome database project
        网址：http://www.ensembl.org/
   5.6	The Gene Disease Associations Database DisGeNET
        网址：http://www.disgenet.org/

7. Gene Expression Omnibus (GEO):
   网址：https://www.ncbi.nlm.nih.gov/geo/
   描述：来自美国国家癌症研究所（NCI）的公共功能基因组数据库，它支持基于阵列和序列的数据，并提供了用于查询和下载基因表达谱的工具。
   * [NGS基础 - 测序原始数据下载](https://mp.weixin.qq.com/s/6oJYGxuBE850PyjMhRi3xg)
   * [测序文章数据上传找哪里](http://mp.weixin.qq.com/s/aDINq43Xwas_l4-AdY7xXg)


#### 3.3	Phenotype databases

1. PHI-base:
   网址：http://www.phi-base.org/
   描述：病原体 - 宿主相互作用数据库。

2. 细胞表型数据库
   网址：https://www.ebi.ac.uk/fg/sym
   描述：基于RNAi的细胞表型收集

3. dbGAP
网址：https://www.ncbi.nlm.nih.gov/gap
描述：基因型-表型数据库，来源于GWAS、医学测序、分子诊断等

4. The Human Phenotype Ontology 
   网址：https://hpo.jax.org/app/
   描述：人类疾病表型描述的标准化术语，类比于Gene Ontology. 现有13000个条目和156,000关于遗传病的注释。

5. GWAS central
   网址： https://www.gwascentral.org
   描述：包含2,974,967个SNP与829个MeSH疾病、表型之间的69,986,326个关联。

6. European genome-phenome archive
   网址：https://ega-archive.org
   描述：生物医学研究中涉及的遗传和表型数据关联库

7. Monarch
   网址：https://monarchinitiative.org
   描述：基因型-表型数据库，表型相似性度量
   
8. Cellular Phenotype Database
   网址：http://www.ebi.ac.uk/fg/sym
   描述：存储来自高通量表型研究的数据，可以搜索感兴趣的表型并检索相关靶基因和RNAi
   
9. GenomeRNAi
   网址：http://www.genomernai.org/
   描述：包含来自果蝇和人RNA干扰筛选的表型数据库
   
10. Genomics of Drug Sensitivity in Cancer
   网址：http://www.cancerrxgene.org/
   描述：筛选了多种抗癌疗法人类癌细胞系，通过与基因组数据关联以识别药物靶标，同时为临床应用提供信息

11.  GenomeCRISPR
   网址：http://genomecrispr.dkfz.de/
   描述：用于高通量CRISPR / Cas9筛选实验的数据库

12. Cellular Microscopy Phenotype Ontology (CMPO)
   网址：www.ebi.ac.uk/cmpo/
   描述：CMPO为描述与整个细胞、细胞成分、细胞过程和细胞群体有关的表型特性提供了一种物种中立的词汇。 
   
13. Human Phenotype Ontology (HPO)
   网址：https://hpo.jax.org/app/
   描述：提供了人类疾病中表型异常的标准化词汇

#### 3.4	RNA databases

1. miRBase
   网址：http://www.mirbase.org/
   描述：存储microRNA序列和注释的数据库。

2. Rfam:
   网址：http://rfam.org/
   描述：一个包含非编码RNA（ncRNA）家族和其他类型RNA信息的数据库。

3. RNAcentral
   网址：https://rnacentral.org/
   描述：非编码RNA序列数据库。

### 4. Amino acid / protein databases

####	4.1 Protein sequence databases

1. Swiss-Prot/Uniprot
   网址：https://www.uniprot.org/
   描述：结合了从文献中提取的信息和生物鉴定者评估的计算分析，是一个手动注释的非冗余蛋白质序列数据库。
   
1. Database of Interacting Proteins (Univ. of California)
   网址：https://dip.doe-mbi.ucla.edu/dip/Main.cgi
   描述：记录了实验确定的蛋白质之间的相互作用。

2. DisProt:（打不开了）
   网址：http://www.disprot.org/
   描述：用于注释文献中的蛋白固有无序区域（IDRs）
   * [2018Cell系列最好的调控方式-相变，最强综述，未来以来，你在哪](https://mp.weixin.qq.com/s/32bCVOkYwKqDufdpmFp0pg)

3. InterPro:
   网址：https://www.ebi.ac.uk/interpro/
   描述：通过整合多个蛋白相关数据库，提供了一个方便的对蛋白序列进行功能注释的平台，包括对蛋白质家族、结构域、功能位点的预测。

4. MobiDB:
   网址：http://mobidb.bio.unipd.it/
   描述：内在蛋白质紊乱注释数据库。

5. neXtProt:
   网址：https://www.nextprot.org/
   描述：人类蛋白质数据库。

6. Pfam:
   网址：http://pfam.xfam.org/
   描述：Pfam是蛋白质家族的数据库，包括使用隐马尔可夫模型生成的注释和多序列比对。

7. PRINTS
   网址：http://130.88.97.239/PRINTS/index.php
   描述：蛋白质序列指纹图谱数据库，所谓蛋白质的指纹是指一组保守的序列基序，用于刻画蛋白质家族的特征。

8. PROSITE:
   网址：https://prosite.expasy.org/
   描述：收集了有显著生物学意义的蛋白质位点和序列模式，并能根据这些位点和模式快速并可靠地鉴别一个未知功能的蛋白质序列应该属于哪一个蛋白质家族。

9. Protein Information Resource
   网址：https://pir.georgetown.edu/
   描述：是一个全面的、经过注释的、非冗余的蛋白质序列数据库。可帮助研究者鉴别和解释蛋白质序列信息，研究分子进化、功能基因组，进行生物信息学分析。

10. SUPERFAMILY:
   网址：http://supfam.org/SUPERFAMILY/
   描述：一个包含所有蛋白质和基因组结构和功能注释的数据库。

####	4.2 Protein structure databases

1. Protein Data Bank (PDB)
   网址：http://www.rcsb.org
   描述：一个专门收录蛋白质及核酸的三维结构资料的数据库，以下为PDB成员网站
   1.1 Protein DataBank in Europe (PDBe)：https://www.ebi.ac.uk/pdbe/
   1.2 ProteinDatabank in Japan (PDBj)：https://pdbj.org
   1.3 Research Collaboratory for Structural Bioinformatics (RCSB)：https://www.rcsb.org
   1.4 Worldwide Protein Data Bank：http://www.wwpdb.org/

3. The Protein Protein Interaction Inhibition Database (2PI2db):
   网址：http://2p2idb.cnrs-mrs.fr
   描述：收集了已通过X射线晶体学或核磁共振表征的蛋白质-蛋白质、蛋白质-调节剂复合物结构。

####	4.3 Protein model databases

1. ModBase:
   网址：https://modbase.compbio.ucsf.edu/modbase-cgi/index.cgi
   描述：一个注释比较饭白纸结构模型的数据库。

2. Protein Model Portal (PMP):
   网址：https://www.proteinmodelportal.org
   描述：结合了数个蛋白质结构模型数据库的元数据库，提供模型构建和质量评估等多种交互式服务。

3. Similarity Matrix of Proteins (SIMAP):
   网址：http://cube.univie.ac.at/resources/simap
   描述：基于FASTA序列计算的蛋白质相似性数据库。

4. Swiss-model:
   网址：https://swissmodel.expasy.org
   描述：致力于同源蛋白质的3D结构建模。

####	4.4 Protein-protein and other molecular interactions

1. BioGRID
   网址：https://thebiogrid.org
   描述：蛋白质与遗传相互作用数据库。

3. string
   网址：http://string-db.org/cgi/help.pl?subpage=api
   描述：用于检索相互作用基因/蛋白质的搜索工具
   
5. IntAct
   网址：https://www.ebi.ac.uk/intact/
   描述：为分子交互研究提供免费的开源数据库系统和分析工具。
   
###	5. Signal transduction pathway databases

1. NCI-Nature Pathway Interaction Database
   网址：http://biogps.org/plugin/259/nci-nature-pathway-interaction-database/
   描述：http://www.ndexbio.org/#/ (原来的PID迁移到此新数据库)。
   NDEx提供了一个开源框架，科学家和机构可以共享、存储、操作和发布生物网络知识。

2. Netpath
   网址：http://www.netpath.org/
   描述：人类信号转导通路数据库，拥有45个信号通路，包括在免疫系统调节和癌症调节中起主要作用的通路。

3. Reactome
   网址：https://reactome.org/
   描述：该库覆盖了19个物种的通路研究，包括经典的代谢通路、信号转导、基因转录调控、细胞凋亡与疾病。

   **reactome相关推文：**
   * [生物AI插图素材获取和拼装指导](https://mp.weixin.qq.com/s/bNrWaK-Rd7I7M0In07_XWg)
   * [没钱买KEGG怎么办？REACTOME开源通路更强大](https://mp.weixin.qq.com/s/jI6Gz1JKxnGB9jDRSFjd0g)

4. WikiPathways
   网址：https://www.wikipathways.org/index.php/WikiPathways
   描述：该数据库收录了超过20个物种的通路，其中人类的通路就包含了800多个通路，涵盖了约7500种基因。此外，它还包含了超过1000个代谢产物的通路。

###	6. Metabolic pathway and protein function databases
代谢途径和蛋白质功能数据库

1. BiGG Models
网址：http://bigg.ucsd.edu
描述：该数据库将70多种已发表的基因组规模的代谢网络整合到了一起，并且有一组标准化的BiGG ID。

2. BioCyc Database Collection:
网址：https://biocyc.org
描述：收集了14558个通路/基因组数据库，每一个数据库描述了单个有机体的基因组和代谢通路，同时提供多种用于组学数据导航和可视化的分析工具。

3. BRENDA:
网址：http://www.brenda-enzymes.org
描述：酶数据库，提供酶的分类、命名法、生化反应、专一性、结构、细胞定位、提取方法、文献、应用与改造及相关疾病的数据。

4. HMDB
网址：http://www.hmdb.ca
描述：人类代谢组数据库，包含有关人体中发现的小分子代谢物的详细信息。

5. KEGG PATHWAY Database
网址：https://www.kegg.jp
描述：KEGG是一个整合了基因组、化学和系统功能信息的数据库。把从已经完整测序的基因组中得到的基因目录与更高级别的细胞、物种和生态系统水平的系统功能关联起来是KEGG数据库的特色之一。



7. Reactome（同上）

8. WikiPathways（同上）

###	7. Additional databases

####	7.1 Exosomal databases

外泌体是一类可以由多种细胞类型分泌的胞外囊泡，与其他胞外囊泡如核外颗粒体和凋亡小体不同，外泌体是内吞起源的。外泌体在疫苗、药物递送、细胞间通信的作用以及其作为生物标志物的一种可能来源以及引起了研究人员的极大兴趣，导致外泌体相关研究呈现井喷趋势。相关数据库如下：

1. ExoCarta
网址：http://www.exocarta.org
描述：是一个关于外泌体蛋白、RNA、脂质体的手工数据库。

2. exoRBase
网址：http://www.exorbase.org
描述：将不同疾病血来源外泌体中的circRNA, lncRNA和mRNA进行整理的数据库。

####	7.2 Mathematical model databases

1. Biomodels Database
网址：http://biomodels.caltech.edu
描述：生物模型在线数据库，主要存储数量型生物化学模型。

####	7.3 Taxonomic databases

1. BacDive
网址：https://bacdive.dsmz.de
描述：提供有关细菌和古细菌生物多样性的菌株相关信息。

2. EzTaxon-e
网址：https://www.ezbiocloud.net
描述：基于16S核糖体RNA基因序列鉴定原核生物的数据库。

####	7.4 Radiologic databases

1. The Cancer Imaging Archive (TCIA)
网址：http://www.cancerimagingarchive.net
描述：包含常见肿瘤（肺癌、前列腺癌等）医学图像（MRI、CT等）及相应临床信息（治疗方案细节、基因、病理等）的大规模公用数据库。

2. Neuroimaging Informatics Tools and Resources Clearinghouse
网址：https://www.nitrc.org
描述：神经影像信息学工具和资源交换中心。

###	8. Wiki-style databases

1. Gene Wiki
网址：https://en.wikipedia.org/wiki/Wikipedia:Gene_Wiki
描述：一个基于wiki的基因信息数据库

###	9. Specialized databases

1. Barcode of Life Data Systems
网址：http://www.boldsystems.org
描述：DNA条形码数据库（即生物体内能够代表该物种的、标准的、有足够变异的、易扩增且相对较短的DNA片段），并提供一个分析DNA序列的在线平台。

2. The Cancer Genome Atlas (TCGA)
网址：https://cancergenome.nih.gov
描述：提供使用高通量技术获得的癌症样本数据，包括基因表达谱、拷贝数变异、SNP基因分型、全基因组DNA甲基化等。

3. Cellosaurus
网址：https://web.expasy.org/cellosaurus/
描述：细胞系的在线资源库。

4. Comparative Toxicogenomics Database (CTD)
网址：http://ctdbase.org
描述：CTD（比较毒物遗传数据库），为研究人员提供了集中、综合的各种不同类型分子以及来自各种生物体的毒理学数据。

5. DiProDB
网址：http://diprodb.fli-leibniz.de
描述：收集和分析热力学，结构和其他二核苷酸特性的数据库。

6. Dryad
网址：http://datadryad.org
描述：存放优质数据资源的场所，使科学出版物背后的数据可被发现、可重复使用、可引用。

7. Edinburgh Mouse Atlas
网址：http://www.emouseatlas.org/emap/home.html
描述：小鼠胚胎原位基因表达数据库。

8. EPD Eukaryotic Promoter Database
网址：https://epd.vital-it.ch/index.php
描述：真核基因启动子数据库，提供从EMBL中得到的真核基因的启动子序列，帮助实验研究人员、生物信息学研究人员分析真核基因的转录信号。

9. FINDbase (the Frequency of INherited Disorders database)
网址：http://www.findbase.org
描述：是一个全球治病遗传变异频率的数据库。

10. HGNC (HUGO Gene Nomenclature Committee): 
网址：https://www.genenames.org
描述：负责对人类基因组包括蛋白编码基因， ncRNA基因，甲基因和其他基因在内的所有基因提供一个唯一的、标准的、可以广泛传播的symbol

11. International Human Epigenome Consortium
网址：http://ihec-epigenomes.org
描述：国际人类表观基因组学会，致力于全球表观基因组学领域的发展。

12. MethBase
网址：http://smithlabresearch.org/software/methbase/
描述：在UCSC Genome Browser上可视化的DNA甲基化数据库。

13. Minimotif Miner
网址：http://minimotifminer.org/
描述：短连续功能性肽基序的数据库。

14. NCI-dbGaP
网址：https://www.ncbi.nlm.nih.gov/gap
描述：人类基因型和表型相互作用的数据库。

15.  PubMed
网址： https://www.ncbi.nlm.nih.gov/pmc/
描述：生命科学和生物医学领域的参考和摘要。

16. Oncogenomic databases
网址：https://oglandscapes.irbbarcelona.org
描述：用于癌症研究的数据库汇编。

17. RIKEN integrated database of mammals
网址：http://metadb.riken.jp/metadb/download/SciNetS_ria254i
描述：Riken研究所推广的多个大型项目的综合数据库。

18. TDR Targets
网址：http://tdrtargets.org
描述：专注于热带疾病药物发现的化学基因组学数据库。

20. LNCipedia
   网址：http://www.lncipedia.org/
   描述：人类长链非编码RNA的整合库
   
21. NONCODE
   网址: http://www.noncode.org/
   描述：存储17类（人类，小鼠，牛，大鼠，鸡，果蝇，斑马鱼，小肠，酵母，拟南芥，黑猩猩，大猩猩，猩猩，恒河猴，负鼠和猪）物种非编码RNA（不包括tRNA和rRNA）的数据库

23. Oncomine
   网址：https://www.oncomine.org/resource/login.html
   描述：肿瘤相关基因研究的数据库，整合了GEO、TCGA和已发表的文献等来源的RNA和DNA-seq数据

24. GeneVestigator（GV）
   网址：https://genevestigator.com/  
   描述：一个基因表达的搜索引擎，集成了上万的人工精选、注释的公共芯片实验结果

25. immuneXpresso
   网址：http://immuneexpresso.org/immport-immunexpresso/public/immunexpresso/search  
   描述：immuneXpresso搜索引擎可自动从PubMed摘要中提取高分辨率细胞 - 细胞因子相互作用网络。

