## High-throughput screening(HTS)

[TOC]

#### [1.Definition](#High-throughput screening(HTS))

High-throughput screening (HTS) is a method for scientific experimentation especially used in drug discovery and relevant to the fields of biology and chemistry. Using robotics, data processing/control software, liquid handling devices, and sensitive detectors, high-throughput screening allows a researcher to quickly conduct millions of chemical, genetic, or pharmacological tests. Through this process one can rapidly identify active compounds, antibodies, or genes that modulate a particular biomolecular pathway. The results of these experiments provide starting points for drug design and for understanding the noninteraction or role of a particular location. (wiki)

![](C:\Users\凤羽空\Desktop\细胞生物学小组作业\图片库\1280px-Chemical_Genomics_Robot.jpg)

![](C:\Users\凤羽空\Desktop\细胞生物学小组作业\图片库\Robot_arm_handles_an_assay_plate.jpg)

高通量筛选 (HTS) 是一种科学实验方法，尤其用于药物发现并与生物学和化学领域相关。 使用机器人、数据处理/控制软件、液体处理设备和灵敏的检测器，高通量筛选使研究人员能够快速进行数百万次化学、遗传或药理学测试。 通过这一过程，人们可以快速识别调节特定生物分子途径的活性化合物、抗体或基因。 这些实验的结果为药物设计和理解特定位置的非相互作用或作用提供了起点。 

High throughput screening (HTS) technology refers to experimental methods at the molecular and cellular levels as the basis, using microplates as the experimental tool carrier, performing the test process with an automated operating system, and collecting with sensitive and rapid detection equipment. The experimental result data is analyzed and processed by a computer, and tens of millions of samples are detected at the same time, and the corresponding database is obtained to support the operation of the technical system. It has the characteristics of trace, fast, sensitive and accurate. In short, a large amount of information can be obtained through one experiment, and valuable information can be found from it. （baidu）

高通量筛选(High throughput screening，HTS)技术是指以分子水平和细胞水平的实验方法为基础，以微板形式作为实验工具载体，以自动化操作系统执行试验过程，以灵敏快速的检测仪器采集实验结果数据，以计算机分析处理实验数据，在同一时间检测数以千万的样品，并以得到的相应数据库支持运转的技术体系，它具有微量、快速、灵敏和准确等特点。简言之就是可以通过一次实验获得大量的信息，并从中找到有价值的信息。



#### [2.Challenges in Breeding Industrial Microorganisms（前言/引文）](#High-throughput screening(HTS))

Naturally isolated microorganisms can rarely be directly used for industrial-
scale production because of low yields and weak tolerance to harsh industrial conditions. Various
strategies have been developed to overcome these problems, including reconstructing cell facto-
ries through modifying the physiological functions of the microorganism at the gene level, and by
providing optimum environments for strain growth and product accumulation.

自然分离的微生物很少能直接用于工业规模生产，因为产量低和对恶劣工业条件的耐受力差。为了克服这些问题，已经制定了各种策略，包括通过在基因水平上修改微生物的生理功能，以及通过为菌株生长和产物积累提供最佳环境，重建细胞工厂

To increase the accumulation of target products, several random mutagenesis and rational
engineering approaches, including physical and chemical mutagenesis ,adaptive laboratory
evolution (ALE), and genetic and metabolic engineering[8,9], have been developed. It is
crucial to develop methods for rapidly screening microbial strains in a large library of mutants
because the probability of a beneficial mutation can be very low ($<1/10^5$). The efficiency of
conventional screening is significantly limited by low throughput and slow detection methods,
leading to high costs for screening large numbers of mutants . Therefore, HTS procedures
have been widely used to isolate high-producer microbial cell factories (Figure 1, Key Figure) 

为了增加目标产物的积累，已经开发了几种随机突变和合理的工程方法，包括物理和化学突变、适应性实验室进化(ALE)[7]和遗传和代谢工程学。在大量的突变体库中快速筛选微生物菌株是至关重要的，因为有益突变的概率非常低($<1/10^5$)。常规筛选的效率受到低通量和缓慢检测方法的严重限制，导致筛选大量突变体的成本高。因此，HTS  被广泛用于分离高产微生物细胞工厂(图1，key figure)



​		**Cell Factories for Product Synthesis Facilitated by High-throughput Screening(HTS)**



![你](C:\Users\凤羽空\Desktop\细胞生物学小组作业\图片库\cell_factory .jpg)



figure 1 : Based on cell factories, substrates (ethanol, glucose, starch, etc.) are converted into a series of products (amino acids, organic acids, alcohols, vitamins,flavonoids, terpenoids, etc.). Common microbial cell factories include bacteria, yeasts, actinomycetes, and fungi. The performance of these microorganisms in accumulating target products can be improved by HTS for intracellular products based on fluorescence-activated cell sorting (FACS) and screening of extracellular
products based on microfluidics.

基于细胞工厂，底物(乙醇，葡萄糖，淀粉等)被转化为一系列产品(氨基酸，有机酸，醇，维生素，黄酮类，萜类等)。常见的微生物细胞工厂包括==细菌、酵母菌、放线菌和真菌==(从左往右)。利用流式细胞荧光分选技术和基于微流控技术的细胞外产物筛选技术进行细胞内产物的筛选，可以提高这些微生物积累靶产物的性能。

so how to select industrial microorangisms?

Two aspects need to be carefully considered in the selection of industrial microorganisms:
how to **expand the scope of the screening** (**generation of a diverse screening library and enabling**
**technologies for expanding the search range**), and how to **enhance the recognition of**
**target products** (**analytical methods to detect specific target products biosynthesized from**
**mutated or engineered microorganisms**)

在选择工业微生物时，需要认真考虑两个方面:==如何扩大筛选范围==(生成多样化的筛选库和扩大搜索范围的使能技术)  ，以及==如何提高对目标产品的识别==(检测由突变或工程微生物合成的特定目标产品的分析方法)。

This review mainly focuses on current strategies and future perspectives of HTS procedures ranging from mutant library generation, enabling technologies for expanding the search range, to the analytical methods used for HTS. Some of the most recent advances and benefits of HTS technology are summa-
rized in Box 1.

本文主要介绍HTS技术的研究现状和发展前景，包括突变体库的建立、扩大搜索范围的使能技术，以及用于HTS的分析方法等。Box 1总结了HTS技术的一些最新进展和优点



![](C:\Users\凤羽空\Desktop\细胞生物学小组作业\图片库\Advantafes of HTS technology.png)

Box1：

HTS在分子和细胞层面上已经很成熟了。它将自动化和微定量实验与大规模数据分析相结合。自动化步骤包括采样、将样品稀释到合适的检测范围、转移样品和显色剂、混合样品、洗涤细胞、显色反应或酶联反应、颜色或荧光检测、数据分析和改良菌株的收集。HTS最早是在20世纪90年代初开发出来的，随后产量的增加进一步刺激了检测小型化、自动化和机器人技术的发展。HTS现已演变为超通量筛选(UHTS)。HTS技术已成为一种常规的实验室技术，广泛应用于工业生物技术的基础研究和应用研究。随着菌落拾取器、液体处理系统、流式细胞荧光分选(FACS)和液滴微流体等新设备的开发，HTS技术的范围已经大大扩大。与传统的筛查方法相比，HTS技术具有显著的优势，包括：

(I)更高效的自动化操作-先进的设备改善了HTS的自动化，防止了潜在的污染和人为错误；

(Ii)需要更少的人力资源-建立自动化操作系统以及使用微孔板和流式细胞仪的培养和分析模式显著降低了劳动力成本；

(Iii)更灵敏和准确-新的分析方法通过检测与目标代谢物含量相关的变化，实现了快速和准确的筛查；

(Iv)样品体积更小--可靠的定量只需要几微升(微板)甚至纳米升(液滴)，大大降低了培养基和试剂的成本。

#### [3 Diverse Screening Library: Mutagenesis and Evolution（多样化筛选文库：诱变与进化）](#High-throughput screening(HTS))

##### [3.1Enrichment and Acclimation（从自然文库中富集与驯化）](#High-throughput screening(HTS))

自然界中存在多种微生物，包括古生菌、细菌、酵母菌、放线菌和真菌。这些微生物通常会积累有用的产品。通过长期适应环境因素，包括pH、温度、渗透压、辐射和诱变物质，可以增强这一能力。因此，积累特定发酵产物的微生物菌株首先从自然文库中富集和驯化（==口述即可==）

The general procedure for screening for a specific strain in a ==natural library== contains the following steps: 

(i) collecting samples rich in the target strain （收集富含目标菌株的样本）

(ii) enriching the target strain with a specific medium（用特定培养基富集目标菌株）

(iii) separating pure species （分离纯种）

(iv) determining the performance of the separate strains（确定分离菌株的性能）

(v) identifying the most promising strain through sequencing analysis（通过测序分析确定最有希望的菌株）

##### [3.2 Mutagenesis Technologies（诱变技术）](#High-throughput screening(HTS))

1. ###### physical mutagenesis approaches ：(Figure 2A)

   - UV light

   - α-rays

   - β-rays

   - γ-rays

   - X-rays

2. ###### chemical mutagenesis approaches:    (Figure 2A)

   - alkylating agents （烷基化试剂）

   - base analogs (碱基的类似物)

   - antibiotics （抗生素）

   - novel mutation methods

3. ###### novel mutation methods

   - atmospheric and room temperature plasma (ARTP)[17–19]（大气和室温等离子体）

   - heavy ion irradiation[20,21]（重离子辐射）

     ==@小组成员，这两个可以稍微介绍下，前面就稍微讲一讲简单原理即可，后续我会继续润色下==

     这两种方法的突变率更高，突变位点更随机，不需要有毒有害的化学物质

4. ###### Adaptive Laboratory Evolution (ALE) （适应性的实验室进化）(Figure 2B)

​			Typical applications of this method include ：

​					(i) adapting microorganisms to tolerate harsh environ-mental stresses such as high osmotic pressure, low/high pH, or high/low temperature;

​						(使微生物适应严酷的环境压力，如高渗透压、低/高pH或高/低温)
​					(ii) improving the capacity of strains with respect to growth rate, substrate consumption, or product accumulation

​					(iii) activating potential pathways to synthesize nonnative products or consume nonnative substrates 

​							（激活合成非自身合成产品通路或消耗非自身底物的潜在途径）



​		==eVOLVER== and ==the microdroplet microbial culture (MMC) system== have been designed for microbial high-throughput 			cultivation and adaptive evolution.

eVOLVER【4】和微滴微生物培养(MMC)【5】系统被设计用于微生物的高通量培养和适应性进化

@小组成员，这里重点来了重点介绍下：

==Evolver==是一种瓶内连续培养系统，可以表征酵母和细菌的适应性生态位。它可以有效地平衡吞吐量、重复性和质量。构建了一个配备多个传感器的微型止血器系统来表征不同条件下的酵母生理

==MMC==基于将微滴产生芯片与检测模块相结合。这些系统能够以较低的成本实现高通量筛选。

​																												**Evolver**

![](C:\Users\凤羽空\Desktop\细胞生物学小组作业\图片库\eVOLVER流程图.webp)

5. ###### Directed Evolution（定向进化)

Directed evolution is a powerful method for engineering enzymes and has been widely employed in industrial biosynthesis processes. it can be divided into nonrational design, rational design, and semirational design according to the methods used for building mutant libraries。

定向进化是一种强有力的酶工程方法，在工业生物合成过程中得到了广泛的应用。根据构建突变体文库的方法不同，可分为==非理性设计==、==理性设计==和==半理性设计==。(Figure 2C)

- Nonrational design is a random evolution strategy that does not require in-depth understanding of
   enzyme sequence and structure, and the main models include error-prone PCR, DNA shuffling,
   and saturation mutagenesis.(非理性设计是一种不需要深入了解酶序列和结构的随机进化策略，其主要模型包括容易出错的pcr、dna改组和饱和突变。）
- Rational design is based on smart computation strategies to simulate the kinetics and evolution of natural enzymes, through which target mutants can be screened in a more efficient way（合理的设计是基于智能的计算策略来模拟天然酶的动力学和进化，通过它可以更有效地筛选目标突变体。）
- Semirational design is established by combining nonrational and rational designs. A series of semirational strategies have been devised, and semirational design is currently the most widely applied route because it takes advantage of sequence space and screening scale （半理性设计是通过将非理性设计和理性设计相结合而建立的。人们已经设计出了一系列的半循环策略，其中半循环设计由于利用了序列空间和筛选尺度，是目前应用最广泛的一种策略）

6. ######  Random Assembly-Based Strategies 🤷‍♀️这一段比较难 （基于随机装配的策略）

To construct strain libraries in a more rational manner, many random assembly-based strategies
have been established, such as the random assembly of promoter–5′-UTR (5′-untranslated
region) complexes with genes , multiplex automated genome engineering (MAGE) **ePathBrick**,**CasEMBLR**, and **COMPASS** (Figure 2D)

为了以更合理的方式构建菌株文库，已经建立了许多基于随机组装的策略，例如启动子-5‘-UTR(5’-非翻译区)复合物与基因的随机组装、多重自动化基因组工程(**MAGE)**、**ePathBrick**、**CasEMBLR**和**COMPASS**。(Figure 2D)

用启动子-5‘-UTR复合体随机组装基因是优化目标产物生物合成途径的最直接的策略。MAGE，它最初是由INE开发的。Coli，c和n通过快速和连续地修饰染色体上的多个位点来实现大规模的编程和进化。它的升级版CRMAGE是在CRISPR/CAS9和λRed介导的重组工程的基础上开发的。此外，还为真核生物(如酿酒酵母)建立了**Emage**。**EPathBrick**方法基于四对等尾链中的载体，为快速设计和优化代谢途径提供了一个通用的平台。**CasEMBLR**是一种无标记的活体多基因组装方法，它可以将含有同源序列的DNA片段整合到基因组的特定位点上。酿酒厂。配备了多位点**CRISPR/CAS9**介导的修饰的COMPASS已被用于生产β-胡萝卜素以及联合生产β-紫罗兰酮和生物传感器响应型柚皮苷元。这些随机组装策略可用于构建具有大量不同功能和调节单元的大规模文库，这些库可能以灵活的方式相互作用。

​																	**Figure 2 Methods for mutagenesis**

![](C:\Users\凤羽空\Desktop\细胞生物学小组作业\图片库\Mutagenesis Technologies.jpg)

#### [4. Expanding the Search Range: Enabling Technologies（现有的技术可以用来扩大筛选范围）](#High-throughput screening(HTS))

##### [4.1 Spectroscopy Equipment（光谱分析）](#High-throughput screening(HTS))

**Mi-croplate readers** are the most commonly used equipment in HTS. Upgraded versions include a
**multilabel plate reader**——a single desktop device with multiple detection modes

微板检测器是HTS中最常用的设备。升级版包括多标签板检测器（具有多种检测模式的基于桌面端的设备）

A detection wavelength in the range 200–1000 nm can be used on a multilabel plate reader to detect absorbance,fluorescence intensity, time-resolved fluorescence,fluorescence polarization, and chemiluminescence . This approach been widely applied for detecting cell apoptosis or growth, metabolite content, enzyme activity, etc.

在200-1000  nm范围内的检测波长可以在多标签板阅读器上使用，以检测吸光度、荧光强度、时间分辨荧光、荧光偏振和化学发光。该方法被广泛应用于**细胞凋亡或生长、代谢物含量、酶活性等检测**。

==以下是重点==

In addition, researchers have also developed devices that can detect an extended range of chemicals based on Raman。 Fourier transform IR , and near-IR  spectra. Some of these devices have been further developed for high-throughput single-cell detection, analysis, and sorting by **exploiting fluorescence-activated cell sorting (FACS)**,**microfluidics**, and **optical tweezers**

傅立叶变换IR和近IR光谱。通过利用**流式细胞荧光分选(FACS)**、**微流控技术**和**光学镊子**，这些设备中的一些已经被进一步开发用于高通量单细胞检测、分析和分选

##### [4.2 Automated Systems](#High-throughput screening(HTS))

 HTS mainly includes a **colony picker（菌落拾取器）**, a **liquid-handling system（液体处理系统）**, and **a multifunctional microplate reader（多功能微板读取器）** which **can be connected and operated under the control of a software system.（可在软件端被控制）** In addition, a series of accessory devices have been modified or redesigned for integration into a HTS system, including PCR machines, centrifuges, refrigerators,and sterilization and packaging systems.

HTS主要包括菌落拾取器、液体处理系统和可在软件系统的控制下连接和操作的多功能微板读取器。此外，还对一系列附件设备进行了改装或重新设计，以集成到HTS系统中，包括PCR机器、离心机、冰箱以及灭菌和包装系统。

​							



​									**Figure 3 Pipelines with Different Screening Throughputs.**

![](C:\Users\凤羽空\Desktop\细胞生物学小组作业\图片库\compostion of  HTS.jpg)

==图片说明==：

与传统的筛选方法相比，基于菌落筛选、流式细胞荧光分选(FACS)和液滴微流控技术的高通量筛选(HTS)的规模和效率已逐步提高。

- (A)以平板法为基础的传统筛分管道，筛分规模为$10^3-10^4$

- (B)HTS技术管道，以菌落采集器为基础，筛查范围为$10^4-10^5$。

- (C)基于FACS的HTS管道(UHTS)，筛查规模为$10^8-10^9$。

- (D)基于微流控技术和流式细胞仪的HTS合成流水线，筛选规模为$10^8-10^9$，提高了效率。






##### [4.3 FACS](#High-throughput screening(HTS))（流式细胞荧光分选技术）/（Fluorescence activated Cell Sorting）

介绍FACS之前让我们先看看什么是**FC（流式细胞术）**

**Flow cytometry (FC)** can quickly analyze multiple parameters of a single cell and rapidly classify
target groups in multiple ways. Information from cells can be accurately detected using FC,
including cell density and size, internal complexity, and other fluorescence signals. FC is a prom-
ising technique for HTS owing to its ability to perform simultaneous quantitative and qualitative
analyses 

**流式细胞术(FC) **可以快速分析单个细胞的多个参数，并以多种方式快速对目标群体进行分类。使用FC可以准确地检测来自细胞的信息，包括**细胞密度和大小**、**内部复杂性和其他荧光信号**。FC是一种很有前途的高通量筛选技术，因为它能够**同时进行定量和定性分析**

 FACS equipped with FC was developed to screen target cells at the single-cell level with high purity and throughput

配备FC的流式细胞仪(FACS)，是用于**在单细胞水平筛选高纯度和高产量的靶细胞**

 FACS is well known for its ultra-high sorting speed, reaching up to 106cells/s. However, the main disadvantage of FACS is its high nonspecific background, and FACS-screened strains need to be further rescreened by a microplate-based HTS process.

FACS以其超高的分选速度而闻名，最高可达$10^6$个细胞/秒。然而，FACS的**主要缺点**是其**非特异性背景较高，FACS筛选的菌株需要通过==微孔板HTS技术==进行进一步的再筛选**。

Most target products in industrial biotechnology are extracellular products that avoid intracellular
feedback inhibition and can also withstand downstream processing. FACS can only be used for
the analysis of intracellular or membrane-bound products that generate fluorescence signals that
correlate with the target compounds , and the use of FACS for analyzing extracellular products is challenging. Microfluidic FACS, which combines microfluidics and cell sorting, can overcome the limitations of traditional FACS, and has attracted considerable interest owing to its cost effective identification and separation methods

工业生物技术的目标产物大多是胞外产物，既能避免细胞内反馈抑制，又能抵抗下游加工。流式细胞仪只能用于分析产生与目标化合物相关的荧光信号的细胞内或膜结合产物，而使用流式细胞仪分析胞外产物具有挑战性。**微流控FACS结合了微流控技术和细胞分选技术，克服了传统FACS的局限性，以其经济高效的鉴定和分离方法引起了人们的极大兴趣。**

注：这里面又多了一个新词==微流控FACS==

下面就隆重介绍下这个所谓的**微流控流式细胞荧光分选技术**   



##### [4.4 Microfluidics Technology](#High-throughput screening(HTS))(微流控技术)

Microfluidics is a technique for manipulatingfluids at the microliter to picoliter scale. It is an emerg-
ing interdisciplinary technology involving chemistry,fluid physics, microelectronics, materials, and
biology. Microfluidics technology generally employs a microfluidic chip, which is known as a 'lab
on a chip' owing to its ability to cover the most basic functions of biological and chemical labora-
tories. Based on microfluidic chip technology, a droplet-based microfluidic system has been de-
veloped for independent single-cell analysis. This has been used in several applications, such as
screening for overconsuming/secretory phenotypes and directed enzyme evolution, given its ad-
vantages that include high sensitivity, quantitative readout, and accuracy.

微流体技术是一种在微升到皮升尺度上操纵流体的技术。它是一门新兴的交叉学科，涉及化学、流体物理、微电子学、材料和生物学。微流控技术通常采用微流控芯片，由于其能够覆盖生物和化学实验室的最基本功能，因此被称为“芯片上的实验室”。**基于微流控芯片技术，研制了一种基于液滴的单细胞独立分析微流控系统**。鉴于它的高灵敏度、定量读数和准确性等优点，它已被用于几个应用，如筛选过度消耗/分泌表型和定向酶进化。

Microfluidic chips can be designed that achieve packaging of single cells in a single droplet. Pro-
vision of substrates that generatefluorescence signals proportional to product concentration can
facilitate FACS analysis of the packaged droplets. The screening efficiency of droplet-based
microfluidic systems can be significantly enhanced by combining them with advanced methods。

微流控芯片可以设计成在==**单个液滴中实现单个细胞的封装**==。提供能够产生与产品浓度成正比的荧光信号的底物可以促进对包装液滴的流式细胞仪(FACS)分析。液滴微流控系统与先进的筛选方法相结合，可以显著提高微流控系统的筛选效率。

 In addition, some detection techniques, such as mass spectrometry, Raman spectroscopy, and capillary approaches, can be integrated into a droplet-based microfluidic system for further expansion of the universality of the screening procedure [60,71,72]. Until recently the most obvious disadvantage of the microfluidic droplet method is that the encapsulating speed for obtaining uniform droplets is around$10^3-10^4$/s, which is **far below that of FACS**. Tailor-made microfluidic chips and high-performance droplet-stabilizing surfactants can alleviate this problem.

此外，一些检测技术，如质谱、拉曼光谱和毛细管方法，可以集成到基于液滴的微流控系统中，以进一步扩大筛查程序的普适性。到目前为止，微流控液滴方法最明显的缺点是获得均匀液滴的包覆速度在$10^3-10^4$/s,左右，远远低于FACS。量身定做的微流控芯片和高效稳定液滴的表面活性剂可以缓解这一问题。



##### [4.5 High-Throughput Culture Systems](#High-throughput screening(HTS))(高产的培养技术)

Miniaturization is an important characteristic of HTS because it can reduce the amounts of biological and chemical samples that are required for analysis [63,73]. In general, high-throughput analysis is conducted in 96- or 384-well microtiter plates (MTPs), whereas high-throughput culture is mainly performed in deep 24-, 48-, and 96-well MTPs because of the need for culture medium and oxygen. High-throughput culture in MTPs would obviously increase the scope for screening target strains. To achieve a mixing effect in MTPs comparable with that of shakeflasks, shakers for MTP cultures should reach 800–1000 rpm, whereas a typicalflask shaker speed is ~100–300 rpm. In addition,**sandwich lids** are also useful for long-term MTP culture because both the rate of evaporation of fermentation broth and cross-contamination between wells can be significantly reduced

小型化是分析所需生物和化学样品的一个重要特征。一般来说，高通量分析是在96孔或384孔的**微滴定板(MTP)**中进行的，而高通量培养主要是在**24孔、48孔和96孔的深孔MTP**中进行的，因为需要培养基和氧气。在MTP中进行高通量培养将明显增加筛选目标菌株的范围。为了在MTP中获得与摇瓶相当的混合效果，MTP培养的摇床转速应达到800-1000rpm，而摇瓶摇床的典型速度为100-300rpm。此外，**三明治盖**对长期培养MTP也很有用，因为发酵液的蒸发速度和井间的交叉污染都可以显著降低。

奇怪的词汇又多了一个 **sandwich lids**??

An ideal microculture device should generally be able to accurately reproduce large-scale cultivation conditions and reflect the physiological metabolism and production capacity of the microorganism . Traditional rescreening is usually performed in shake flasks and bioreactors in sequence. However, the 	process parameters in shake flasks are difficult to measure and regulate in real time, thus seriously limiting the amplification of an improved strain in a bioreactor .**Microbioreactors** have been designed for high-throughput optimization to replace traditional two-step fermentation in shake flasks and bioreactors by a one-step integrated process. The evolved design is further equipped with a waterless temperature-control system, microvalve-controlled feeding, and noninvasive optical pH and dissolved oxygen (DO) biosensors. However, these techniques need further improvement, especially regarding the detection range and sensitivity of pH and DO electrodes in the very limited culture volume 

一个理想的微培养装置一般应该能够准确地复制大规模的培养条件，并反映微生物的生理代谢和生产能力。传统的复筛通常是在**摇瓶和生物反应器中按顺序进行**的。然而，**摇瓶中的工艺参数很难实时测量和调节**，因此严重限制了改良菌株在生物反应器中的放大。微生物反应器是为高通量优化而设计的，用一**步集成工艺取代了摇瓶和生物反应器中传统的两步发酵**。这个进化设计进一步**配备了无水温度控制系统**、**微阀控制进料以及非侵入式光学pH和溶解氧(DO)生物传感器**。然而，这些技术还需要进一步改进，特别是在非常有限的培养量下，pH和DO电极的检测范围和灵敏度方面。



#### [5. Highlighting Target Compounds: Detection Methods](#High-throughput screening(HTS))(突出目标化合物：检测方法)

##### [5.1 UV/Visible Spectroscopy-Based Screening（紫外或者基于可见光光谱的筛选方法）](#High-throughput screening(HTS))

 These can be divided into direct and indirect detection methods (Figure 4A). Products with a relatively complex molecular structure or innate color properties, such as avermectin [10], cephalosporin C [74], lycopene , and p-coumaric acid , can be screened through direct measurement of absorbance. Some products that have no obvious absorbance characteristics for direct detection can be detected by inclusion of pH indicators, chelation with metal ions, or coupling with enzymatic or chemical reactions. For example, if a strain accumulates a single type of organic acid as the target product, a screening procedure
can be established by adding suitable pH indicators . A low pH not only indicates that the strain accumulates more organic acid, but also shows that the strain has the capacity to tolerate a lower pH. For more specific detection of a target organic acid, such as pyruvic acid, a screening process can be established by adding a chelation ion that generates a detectable yellow complex. In addition, screening methods have been developed based on chemical or coupled enzyme reactions which establish quantitative relationships between target metabolite concentration and chromogenic substances such as ATP/ADP [83] and NAD(P)+[84]. Some typical HTS methods and their applications in screening industrial microorganisms are listed inTable 1. A large number of selected strains with improved performance have been successfully applied in industrial-scale production.

这些方法可分为**直接检测法**和**间接检测法**(图4A)。**具有相对复杂的分子结构或天然颜色特性的产品**，如阿维菌素、头孢菌素C、番茄红素和对香豆酸，可以**通过直接测量吸光度来筛选**。一些**没有明显吸收特性可直接检测的产品**，可**通过加入pH指示剂、与金属离子螯合或与酶反应或化学反应耦合的方法进行检测**。

~~例如，如果菌株积累了单一类型的有机酸作为目标产物，则可以通过添加合适的pH指示剂来建立筛选程序。低pH不仅表明该菌株积累了较多的有机酸，而且表明该菌株具有耐低pH的能力。为了更具体地检测目标有机酸，例如丙酮酸，可以通过添加生成可检测的黄色络合物的螯合离子来建立筛选过程。~~

此外，还发展了**基于化学或偶联酶反应的筛选方法**，这些反应**建立了目标代谢物浓度与显色物质(如ATP/ADP）和NAD(P)+)之间的定量关系**。表1列出了几种典型的HTS方法及其在工业微生物筛选中的应用。大量筛选出的性能较好的菌株已成功应用于工业化生产。

##### [5.2 Fluorescence Spectroscopy-Based Screening（基于荧光光谱技术的筛查）](#High-throughput screening(HTS))

Similarly to UV/visible spectroscopy-based HTS,fluorescence spectroscopy-based HTS can be
divided into direct and indirect detection methods according to the characteristics of the target
product (Figure 4B). For instance, riboflavin hasfluorescence excitation/emission wavelengths
at 450/518 nm, and Yarrowia lipolytica mutants with increased riboflavin production could be
screened based onfluorescence intensity at 518 nm [54]. The use offluorescent dyes/probes
for screening is a common approach, such as labeling dead or live cells with dyes [10], analyzing
lipids and single-cell oils with Nile red [85,86], and quantifying menaquinone and polymalic acid
with rhodamine [87,88]. Interestingly, before screening based on Nile red, the density of
Y. lipolyticawas used for prescreening of more efficient lipogenic strains through the identification
offloating cells [89]. Methods based on chemical or enzyme-coupled reactions that generate
fluorescent signals have also been widely used for the efficient selection of improved industrial microorganisms [38,48]. HTS based on fluorescence can achieve ultra-HTS (uHTS) because it per-
mits an increase in speed and a reduction in scale comparable with FACS. Fluorescence
spectroscopy may be further expanded to biosensor-based HTS.

与基于紫外/可见光光谱的HTS技术类似，基于荧光光谱的HTS技术可根据目标产品的特性分为**直接检测方法**和**间接检测方法**(图4B)。

~~例如，核黄素的荧光激发/发射波长在450/518  nm，根据518  nm的荧光强度可以筛选出核黄素产量增加的亚罗维氏脂质体突变株。使用荧光染料/探针进行筛选是一种常用的方法，例如用染料标记死亡或活细胞，用尼罗红分析脂质和单细胞油，用罗丹明定量孟喹酮和多聚马来酸。有趣的是，在基于尼罗红的筛选之前，解脂耶尔森氏菌的密度被用来通过鉴定脱落细胞来预筛选更有效的产脂菌株。~~

**基于产生荧光信号的化学**或**酶偶联反应的方法**也被广泛用于高效选择改良的工业微生物。基于荧光的HTS技术可以实现超HTS技术(UHTS)，因为它允许速度的提高和规模的缩小，可以与FACS相媲美。荧光光谱学可以进一步扩展到基于生物传感器的HTS技术。

##### [5.3 Biosensor-Based Fluorescence Spectroscopy Screening(基于生物传感器的荧光光谱筛选)](#High-throughput screening(HTS))。 (Figure 4C)

 A biosensor consists of a sensor and a reporter. The sensor identifies specific intracellular metabolites, while the reporter generates quantitative signals through a series of programmed genetic circuits linked to the sensor signal. A series of biosensors have been developed for uHTS based on this principle. Biosensors are generally of two types–protein-based biosensors and nucleic acid-based biosensors. Most protein -based biosensors are based on transcription factors (TFs) and engineered fluorescent proteins (FPs), whereas nucleic acid-based biosensors mainly include RNA riboswitches, RNA Spinach, and structure switching-based DNA biosensors 

生物传感器由**传感器**和**传导器**组成。**传感器识别特定的细胞内代谢物**，而**传导器**通过一系列与传感器信号相连的程序化遗传电路**产生定量信号**。

基于这一原理，已研制出一系列用于HTS的生物传感器

生物传感器通常有两种类型-基于蛋白质的生物传感器和基于核酸的生物传感器。

大多数**基于蛋白质的生物传感器是基于转录因子(TF)和工程荧光蛋白(FP)的**，

而**基于核酸的生物传感器**主要包括：

- RNA核糖开关
- RNA Spinach
- 基于结构转换的DNA生物传感器



##### [5.4 Electrochemical Sensor (ES)-Based Screening(基于电化学传感器(ES)的筛选)](#High-throughput screening(HTS))

 In HTS, ES techniques have been employed to enhance the activity of enzymes associated with NAD(P)H or H2O2, mainly oxidoreductases and oxidases (Figure 4D); however, few studies have addressed ES applications for the detection of particular fermented products in industrial biotechnology.

在HTS技术中，ES技术被**用来增强与NAD(P)H或$H_2O_2$相关的酶的活性**，主要是**氧化还原酶和氧化酶**；然而，很少有研究涉及ES在工业生物技术中检测特定发酵产物的应用。



##### [5.5 Screening Based on Advanced Spectroscopic Techniques(基于先进光谱技术的筛选)](#High-throughput screening(HTS))

To enhance the sorting efficiency and obtain industrial producers with specific target phenotypes,
spectroscopic techniques based on advanced instrument platforms such as Raman, Fourier transform IR (FTIR), and Fourier transform near-IR (FTNIR) spectroscopy are being applied in industrial biotechnology (Figure 4E). Raman spectroscopy is based on the Raman effect, and has advantages of rapid, sensitive, nondestructive, and real-time detection. A HTS Raman spectroscopy platform was recently established for label-free screening of single cells and biocatalysts . Similarly to Raman spectroscopy, FTIR and FTNIR spectroscopy are also non-destructive analytical methods with the advantages of high throughput and rapid and automated detection. These two analytical methods have been employed for screening *Aurantiochytrium*  sp. Mucorsp.,and S. cerevisiae. These spectroscopic techniques and their advanced imaging technologies integrated with confocal laser scanning microscopy have great potential in industrial HTS.

为了提高分选效率，获得具有特定目标表型的工业生产者，基于先进的仪器平台(如拉曼、傅立叶等)的光谱技术

**傅立叶变换==红外光谱==(FTIR)**和**傅立叶变换==近==红外光谱(FTNIR)**正在工业生物技术中得到应用(Figure 4E)。拉曼光谱是基于拉曼效应，具有快速、灵敏、无损、实时检测等优点。

最近建立了**HTS拉曼光谱平台**，用于单细胞和生物催化剂的无标记筛选。

与拉曼光谱类似，**FTIR和FTNIR光谱**也是无损分析方法，具有高通量、快速、自动化检测等优点。这两种分析方法已用于**金黄色葡萄球菌**(Aurantiochytrium  sp.)、**毛霉(**Mucorsp.)的筛选当中。

这些光谱技术及其先进的成像技术与共聚焦激光扫描显微镜相结合，在工业HTS领域具有巨大的潜力。



==重点关注这张图== Figure 4 

@小组成员，下面这张图上面的东西明白了就都明白了



​				**Figure 4. General Strategies for Establishing High-Throughput Screening (HTS).**

![](C:\Users\凤羽空\Desktop\细胞生物学小组作业\图片库\1-s2.0-S0167779920300019-gr4_lrg.jpg)

 **Figure 4说明：**

Different strategies have been employed to highlight the target products for establishing HTS for screening high-performance microorganisms.

(A) Absorbance-based strategies include (1) direct detection based on the molecular structure or an
innate color property of the target product; (2) indirect detection by, for example, the addition of a pH indicator, metal ion chelation, and coupling with enzymatic or
chemical reactions. 

**(A)基于吸光度的策略包括(1)基于目标产品的分子结构或固有颜色属性的直接检测；(2)通过例如添加pH指示剂、金属离子螯合以及与酶反应或化学反应耦合的间接检测。**

(B) Fluorescence-based strategies include (1) direct detection based on innate fluorescence of the target product; (2) indirect detection using a dye/pH probe, metal ion, and coupling with enzymatic or chemical reaction. 

**(B)基于荧光的策略包括：(1)基于目标产品的天然荧光的直接检测；(2)使用染料/pH探针、金属离子以及与酶反应或化学反应耦合的间接检测。**

(C) Electrochemical Sensor (ES)-based strategies. 

**(C)基于电化学传感器(ES)的策略**

(D) Biosensor-based strategies including
(1) transcription factors (TFs); (2)fluorescent proteins (FPs) and detection by Förster resonance energy transfer (FRET); (3) RNA riboswitch based on ribosome binding
sites (RBS); (4) RNA riboswitch based on ribozymes; (5) RNA Spinach; (6) DNA biosensors. 

**(D)基于生物传感器的策略，包括(1)转录因子(TF)；(2)荧光蛋白(FPs)和Förster共振能量转移(FRET)检测；(3)基于核糖体结合位点(RBS)的RNA核糖开关；(4)基于核酶的RNA核糖开关；(5)RNA  Spinach；(6)DNA生物传感器。**

(E) Special spectrum-based strategies such as Raman (RS), Fourier transform IR (FTIR), and Fourier transform near-IR (FTNIR) spectroscopy.

**(E)基于光谱的特殊策略，例如拉曼(RS)、傅里叶变换红外(FTIR)和傅立叶变换近红外(FTNIR)光谱。**





#### [6. Concluding Remarks and Future Perspectives(结束语和未来展望)](#High-throughput screening(HTS))

对前文进行简单的总结：

MTP-based HTS techniques have improved both automation and throughput for obtaining indus-
trial microorganisms with better phenotypes, resulting in less labor-intensive and more efficient
workflows. FACS- and microfluidics-based HTS techniques, in combination with differentfluores-
cent probes and biosensors, have significantly improved screening efficiency from $10^5$/day to
/$10^{11}$day.

**基于MTP的HTS技术****提高了获得表型更好的工业微生物的**自动化和吞吐量**，从而减少了劳动密集型，提高了工作流程的效率。**基于FACS和微流控技术的HTS技术**与不同的荧光探针和生物传感器相结合，大大**提高了筛查效率**，从$10^5$/天提高到$10^{11}$/天。 

==注意区分二者==

目前依旧存在的不足：

However, an enzyme harboring 1000 amino acid residues could theoretically generate up to $19^{1000}$variants, and current screening throughput is far below this magnitude.

然而，一种含有1000个氨基酸残基的酶理论上可以产生高达$19^{1000}$个变异体，而目前的筛选吞吐量远远低于这个数量级。

展望未来：

 the development of screening techniques that are more efficient than FACS-based methods, using nanotechnology and electronic techniques, is an important goal. Nanotechnology is an emerging technology in which the nanopores and nanoprobes have been used to analyze tumor cells and pathogenic bacteria. Combined with the microfluidics and other measurement techniques, these technologies have great potential for constructing more sensitive biosensor systems to screen a greater diversity metabolites or enzymes, and further enhance screening efficiency.

比基于FACS的方法更有效的筛查技术，**纳米技术**和**电子技术开发**是一个重要的目标。**纳米技术是利用纳米孔和纳米探针分析肿瘤细胞和病原菌的新兴技术。结合微流控技术和其他测量技术，这些技术在构建更灵敏的生物传感器系统以筛选更多多样性的代谢物或酶，进一步提高筛选效率方面具有很大的潜力。**

 Furthermore, advances in artificial intelligence and the advent of big bio-data are set to revolutionize current screening pipelines and further reduce the costs of HTS.

此外，人工智能的进步和大生物数据的出现将彻底改变目前的筛查管道，进一步降低HTS的成本。





































#### 7. References

1. [高通量筛选_百度百科 (baidu.com)](https://baike.baidu.com/item/高通量筛选/3940502)
2. [High-throughput screening - Wikipedia (jinzhao.wiki)](https://en.jinzhao.wiki/wiki/High-throughput_screening)
3. Zeng W, Guo L, Xu S, Chen J, Zhou J. High-Throughput Screening Technology in Industrial Biotechnology. Trends Biotechnol. 2020;38(8):888-906. doi:10.1016/j.tibtech.2020.01.001
4. Wong, B., Mancuso, C., Kiriakov, S. *et al.* Precise, automated control of conditions for high-throughput growth of yeast and bacteria with eVOLVER. *Nat Biotechnol* **36,** 614–623 (2018).
5. Tan, Z.L. et al. (2019) In vivo continuous evolution of metabolic pathways for chemical production. Microb. Cell Factories 18,82

