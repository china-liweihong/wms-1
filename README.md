<span id="_Toc206479396" class="anchor"><span id="_Toc122689566" class="anchor"><span id="_Toc206560056" class="anchor"><span id="_Toc206560144" class="anchor"><span id="_Toc206560381" class="anchor"><span id="_Toc206560491" class="anchor"><span id="_Toc208137520" class="anchor"><span id="_Toc208830627" class="anchor"><span id="_Toc371666004" class="anchor"><span id="_Toc376785377" class="anchor"></span></span></span></span></span></span></span></span></span></span>第二章 系统分析
=====================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================

<span id="_Toc206479398" class="anchor"><span id="_Toc122689568" class="anchor"><span id="_Toc206560058" class="anchor"><span id="_Toc206560146" class="anchor"><span id="_Toc206560383" class="anchor"><span id="_Toc206560493" class="anchor"><span id="_Toc208137522" class="anchor"><span id="_Toc208830629" class="anchor"><span id="_Toc371666009" class="anchor"><span id="_Toc376785382" class="anchor"></span></span></span></span></span></span></span></span></span></span>2.1系统需求分析及设计目标
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### <span id="_Toc371666008" class="anchor"><span id="_Toc376785383" class="anchor"><span id="_Toc206479399" class="anchor"><span id="_Toc122689569" class="anchor"><span id="_Toc206560059" class="anchor"><span id="_Toc206560147" class="anchor"><span id="_Toc206560384" class="anchor"><span id="_Toc206560494" class="anchor"><span id="_Toc208137523" class="anchor"><span id="_Toc208830630" class="anchor"><span id="_Toc371666010" class="anchor"></span></span></span></span></span></span></span></span></span></span></span>2.1.1系统需求分析

企业目前存在的问题是：信息化不足，计算机使用率低，大量的日常工作皆是手工处理，纸面处理。因此工作效率低落，企业内部沟通不及时等等问题很难克服，仓库管理不合理，不能及时根据需要调整库存，不能根据快速的调整库存。

企业希望解决的问题是：

1.  设计一个企业管理信息系统，解决各个业务部门之间缺少信息沟通（即重复劳动）和共享，这两个导致传统仓库管理中占用资源过大的主要问题。

2.  解决企业内部统一的物料编码管理，物流管理中的信息流通。库存积压与物料的配套问题。

3.  完善质量检验，对生产过程中的质量信息进行全面管理，用户反馈，售后服务，并对各种数据进行统计分析。

4.  销售部门能方便地根据预测信息、各仓库的库存信息和客户的要货情况做出货物的调拨计划和改制计划。

5.  随时了解供应商的供货（原材料和添加剂）执行情况、精炼车间的加工（合格、报废、返工等）执行情况及公司的各仓库库存情况，以便随时协调或采取合适的补救措施管理供应商，在供应到货的到期日前，主动与供应商联系，检查及时到货的可能性；对供应商的考核从质量、交货及时程度和价格上给出统计数据。计划过程不太理想，无物料清单，凭经验办事；对计划的执行率未作统计。现有量、在制品、再途库存和历史记录等多方位查询需求。

6.  库存信息与供应和生产等各部门的及时反馈和共享问题信息查询与决策，对集团公司的各种资源与信息进行查询，包括销售、采购、生产、质量、人事、财务等信息数据进行查询、统计与分析，对根据信息作出快速合理的经营决策，增强应变反应能力。

### <span id="_Toc206479400" class="anchor"><span id="_Toc122689570" class="anchor"><span id="_Toc206560060" class="anchor"><span id="_Toc206560148" class="anchor"><span id="_Toc206560385" class="anchor"><span id="_Toc206560495" class="anchor"><span id="_Toc208137524" class="anchor"><span id="_Toc208830631" class="anchor"><span id="_Toc371666011" class="anchor"><span id="_Toc376785384" class="anchor"></span></span></span></span></span></span></span></span></span></span>2.1.2系统设计的目标

本仓库管理软件的目标主要向中小型物流仓储企业开发的仓库管理软件， 仓库能够接受多家客户的委托管理他们的货物存储。能够对仓库内的货物收、发、

存、调、查等操作进行全面的预测、建议、控制和管理。 输出报表，及时反映出货物占用状况、收发与物资的仓储、流向情况，为生产管理和成本核算提供依据，使用户能够实现高效管理。

### <span id="_Toc206479401" class="anchor"><span id="_Toc122689571" class="anchor"><span id="_Toc206560061" class="anchor"><span id="_Toc206560149" class="anchor"><span id="_Toc206560386" class="anchor"><span id="_Toc206560496" class="anchor"><span id="_Toc208137525" class="anchor"><span id="_Toc208830632" class="anchor"><span id="_Toc371666012" class="anchor"><span id="_Toc376785385" class="anchor"></span></span></span></span></span></span></span></span></span></span>2.1.3系统的功能需求

本系统主要需求有：基础数据维护，货物入库，货物出库，盘仓，货物费用计算，货物数量计算，如下图 3.1 所示输出统计报表。

提供一套完备的与企业仓库管理中所需相一致的功能：

（1）建立基本资料信息库，规范所有资料信息。

> （3）高仓库管理的服务水平，最大限度地降低库存量，包括中间库存和在制品的库存，以减少在库存上的资金积压。

（4）最大限度的保证订货任务的按期完成。

（5）提高计划的可能性，实现均衡生产：

（6）集成管理职能，提高管理效率。

系统整体可以分为多个子系统，分别对应某些特定方面的功能。从整体上看，整个系统可以分为8个子系统：

（1）登录管理：包括权限管理，帐户管理，帐户认证，角色分配。

（2）入库管理：包括请购单生成，采购明细，入库。

（3）仓库管理：包括库存明细，查询，出入库，盘点，调拨。

（4）出库管理：包括销售出库。

（5）查询及报表生成

（6）智能库存分析及报警管理：包括决策生成。

系统基本功能图如下所示：

<img src="./media/image1.png" width="415" height="329" />

图2.2.3系统基本功能图

通过调查，要求系统需要有以下功能特点：

&gt; 易用性： 能够像其他普通管理软件一样有较好的用户体验， 方便用户操作， 快速掌握系统操作流程。

&gt; 用户访 问控制： 针对企业中不同用户访问系统， 为了安全性考虑， 对用户划分权限，限制系统操作功能，可以考虑 使用基于角色的权限控制。

&gt; 批量处理： 为了解决企业数据量大,手动输入效率低下的问题， 系统提供了 Excel格式的文件导入导出功能，快速导入到数据库和备份数据库功能。

&gt; 系统快速查询： 支持多条件的模糊查询，可用于自定义报表。

&gt; 系统响应速度快：MySQL 得益于它的数据库引擎，能对不同的系统要求自定义选择，提高系统性能。

&gt; 报表功能：为了满足不同业务员的需求，系统可提供按条件分类的系统报表。

<span id="_Toc376785386" class="anchor"><span id="_Toc206479402" class="anchor"><span id="_Toc122689572" class="anchor"><span id="_Toc206560062" class="anchor"><span id="_Toc206560150" class="anchor"><span id="_Toc206560387" class="anchor"><span id="_Toc206560497" class="anchor"><span id="_Toc208137526" class="anchor"><span id="_Toc208830633" class="anchor"><span id="_Toc371666013" class="anchor"></span></span></span></span></span></span></span></span></span></span>2.2系统的组织结构及功能分析
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

组织结构与功能分析是整个系统分析工作中最简单的一环。组织结构与功能分析主要有三部分内容：组织结构分析、组织结构与业务功能联系分析。在分析组织结构域功能之前我们首先了解一下仓储部门的主要职能。

仓储部主要负责管理企业各类原材料、辅料、产成品、零部件、设备等物资的入库、保管、库存控制、出库、配送等活动，为企业的生产经营活动提供保障，为企业的发展提供服务，具体职能包括以下六大项。

（一）物资检验

1．对企业所采购各类物资、产成品进行入库前的数量清点、单据核对。

2．检查企业所购物资的包装情况，做好记录。

3．将入库前物资检验的结果及时反馈给采购部，以便采购部及时做出相应处理。

（二）物资出入库管理

1．对出入库前的各类物资进行点数或过磅。

2．办理各类物资的出入库手续，检查单据是否填制齐全，单据不全者拒绝出入库。

3．严把出入库物资的质量关：具有质量检验合格报告书的物资才可入库；对出库物资也要进行品质检验，杜绝不合格品投入使用或流入市场。

4．优化出入库流程，保证出入库工作的准确性。

（三）物资存储保管

1．仓库规划，包括规划存放区域，设计各类物资的摆放规则、位置，合理利用仓容及各类资源。

2．各类物资的分类存放、整理和保管。

3．各类库存物资，尤其是设备、备件等的保养。

4．库区的公共卫生管理（防止各类物资受潮、变质等）。

5．仓库的安全、消防管理（做好防火、防盗工作）。

（四）物资定期盘点

1．统计每日出入库物资数量，编制统计日报表，为采购、生产等部门提供准确的库存数据。

2．定期对库存物资进行盘点，记录在库物资的各项数据，定期向财务部提交库存盘点数据。

3．处理盘盈、盘亏、损失等情况。

（五）库存控制

1．核定和掌握各种物资的储备定额，并严格控制，保证库存合理。

2．对各类物资进行动态管理，及时提出采购需求报告。

3．对仓库内发生的滞料、废料予以及时处理。

（六）物资装卸、搬运及配送管理

1．做好各类物资的装卸、搬运、出入库及库内搬移作业。

2．做好各类物资的分拣、拆包，产成品的包装、打包。

3．做好库内物资的理货、配货工作，并及时将物资送达生产现场或指定地点。

4．做好叉车、运输车辆的调度、养护及对驾驶员的管理工作等。

### 2.2.1组织结构分析

组织结构反映一个组织内部部门的划分及其相互之间的关系，通常是通过组织结构图来实现的。下图是按仓库的不同职能设计的仓储部组织结构图，反映了仓储部门内部之间隶属关系。

### 2.2.2组织结构与业务功能联系分析

组织结构图反映了组织内部和上下级关系，但却不能反映组织各部门之间的联系程度、组织各部门的主要业务职能和它们在业务过程中所承担的工作等，这将会给后来的业务，数据流程分析和过程/数据分析等带来困难。通过组织/功能分析，可以反映组织各部门在承担业务时的关系，使组织的功能进一步理顺，提高管理效率。其分析工具组织结构与业务功能联系表。

-   横向表示各组织名称，纵向表示业务功能名，中间栏填写组织在执行业务过程中的作用。

|                          | 检验组 | 入库管理组 | 出库管理组 | 仓储保管组 | 库存管理组 | 装卸搬运组 |
|--------------------------|--------|------------|------------|------------|------------|------------|
| 物资检验                 | \*     |            |            | ×          |            |            |
| 入库管理                 | √      | \*         |            |            |            | ×          |
| 出库管理                 | √      |            | \*         |            |            | ×          |
| 物资存储保管             | ×      |            |            | \*         |            | ×          |
| 物资定期盘点             |        | √          | √          | √          | \*         |            |
| 仓库调拨                 |        | √          | √          | √          | \*         |            |
| 物资装卸、搬运及配送管理 |        | √          | √          |            |            | \*         |

\*：表示该部门是相应业务的执行部门；×：表示该部门是相应业务的辅助执行部门；

√：表示该业务的执行需要用到相应管理部门的数据； 空格：表示该单位与对应业务无关 。

2.3系统的业务流程分析
---------------------

业务流程图是一种描述系统内各单位、人员之间业务关系、作业顺序和管理信息流向的图表，利用它可以帮助分析人员找出业务流程中的不合理流向。

为了调查管理业务流程，调查人员应顺着原系统信息流动的过程逐步地进行，内容包括各环节的处理业务、信息来源、处理方法、计算方法、信息流经去向、提供信息的时间和形态。

从前面的组织结构与业务功能分析可以看出仓库管理系统主要有以下几项业务流程（如图 2-4所示）：

入库管理：采购部门或其他部门的入库单首先要通过检验组的检查，入库前物资检验的结果及时反馈给采购部，以便采购部及时做出相应处理，准确无误后才能提交给入库管理组，入库主管审批后再由库工安排入库，入库完成后再由制表员存档。

出库：有关部门持出库单经出库主管审批后，由出库库工安排出库，入库完成后再由制表员存档。

盘点统计：主要通过对入库、出库进行登账后的管理，对盘点过的数据进行统计、报损或报益，查看是否有缺货现象或发出库存预警。将盘点结果提交给相关部门。

库存调拨：对不同仓库之间的货品进行同价调拨并记录档案。

仓库管理系统业务流程如图2.4所示。

<embed src="./media/image2.png" width="553" height="432" />

图2.4 仓库管理系统业务流程图

2.4系统的数据流程分析
---------------------

前两节关于仓库管理的组织机构和业务流程分析中绘制的组织结构图、业务流程图等图表虽然形象地表达了仓库管理中信息的流动和存储过程，但仍没有完全脱离一些物质要素（如货物、产品等），数据流程分析把数据在组织内部流动的情况抽象地独立出来，不考虑具体的组织机构、信息载体、处理过程、物资和材料等，只从数据流动来考察实际的业务数据处理模式。数据流程分析的目的就是要发现和解决数据流通中的问题，这些问题包括：数据流程不畅，前后数据不匹配，数据处理过程不合理等等。

数据流程分析是通过分层的数据流程图来实现的，下图为本系统的数据流程图。

<embed src="./media/image3.png" width="553" height="286" />

图2.5 仓库管理系统数据流程图

第三章 系统总体设计
===================

在系统分析的基础上，可以进一步对系统设计的具体分析和总体思想进行设计。总体设计主要是对系统做一个概括性的介绍，以及功能模块设计和物理配置方案设计。

<span id="_Toc206479406" class="anchor"><span id="_Toc122689576" class="anchor"><span id="_Toc206560066" class="anchor"><span id="_Toc206560154" class="anchor"><span id="_Toc206560391" class="anchor"><span id="_Toc206560501" class="anchor"><span id="_Toc208137530" class="anchor"><span id="_Toc208830638" class="anchor"><span id="_Toc371666018" class="anchor"><span id="_Toc376785392" class="anchor"></span></span></span></span></span></span></span></span></span></span>3.1 系统功能模块设计
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

采用分解的方法，将系统设计成由相对独立、功能单一的模块组成的结构，它是以系统的逻辑功能和数据流关系为基础，根据数据流程图，借助于一套标准的设计准则和图表工具，通过“自上而下”和“自下而上”的反复，把系统逐层划分为多个大小适当、功能明确、具有一定独立性且容易实现的模块，从而把复杂系统的设计转变为多个简单模块的设计，使系统开发的整体工作量变小。

从企业仓储的功能角度上看， 基于 php开发的仓储管理系统开发的总体任务是要实现企业仓储管理工作的系统化、规范化和自动化。 所以本系统不仅应具备拥有权限的用户实现对系统的管理，还应包含了以下一 些的主要功能模块，每个模块的功能都是按照在调研中搜集的资料及前面的系统分析进行编排制作的。

1.  基础管理：包括往来单位信息管理、员工信息管理、商品信息管理、部门设置、仓库设置等基本信息的录入与设置。

2.  入库管理：管理入仓的货物流水编号，入库类型，入货经办人，卖方单位， 与制单人，用户可以非常方便清晰地输入货品入仓信息，系统会提示用户哪些货品字段是必须输入的，如果用户输入了系统中已经存在的唯一 字段，那么系统将会出现提示信息，终止数据的写入。

3.  出库管理：管理出仓的货物流水编号，出库类型，出货经办人， 买方单位，与制单人。用户可以非常方便清晰地输入货品出仓信息，系统会提示用户哪些货品字段是必须输入的的，如果用户输入了系统中已经存在的唯一字段，那么系统将会出现提示信息，终止数据的写入。

4.  库存管理：包括库存调拨、库存盘点、库存预警等功能,库存管理是建立在基础信息管理及出/入库管理的基础上的，其中也包含了一些智能决策的功能并提供库存查询的功能。

5.  汇总管理：提供各种统计报表的查询，查询条件可以按照要求设定

6.  系统设置：包括操作用户设置，数据备份，数据恢复，系统登录日志等。

系统功能结构图如图4-1所示：

<embed src="./media/image4.png" width="553" height="414" />

<span id="_Toc208830640" class="anchor"><span id="_Toc371666020" class="anchor"><span id="_Toc376785393" class="anchor"></span></span></span>3.2 系统物理配置方案设计
---------------------------------------------------------------------------------------------------------------------------------------------------------------------

本仓库管理系统使用PHP编程，通过WEB技术实现界面，数据库置于WEB服务器中。用户主要通过因特网访问接口界面，经过认证之后就可以进入系统进行信息管理。故而本系统将大部分的数据处理在服务器端进行，对于客户端要求很低，只要是能连接因特网，访问WEB页面，支持JS、CSS等WEB中广泛应用的技术即可。对于服务器端，应对安全性、稳定性要求严格，采用专门的服务器配置，能够24小时长期不间断工作。但在开发阶段，我们仅使用一般的计算机结合Apache + PHP + MySQL软件实现服务器的功能。

<img src="./media/image5.jpeg" width="553" height="365" />

服务器配置要求：

专业的服务器，使用Windows Server 2003等专业的服务器操作系统，系统要求支持PHP、Apache、MySQL最新版本的软件。

客户端配置要求：

台式机、笔记本、智能终端均可，能够接入因特网，支持常见的WEB技术，如HTML、JavaScript、CSS等，有相应的输入设备。

网络配置要求：

如果管理仅限于本地，则仅需将终端与服务器连接于同一局域网；如需在外网访问系统，则需要服务器有专门分配的固定IP地址。

<span id="_Toc206479417" class="anchor"><span id="_Toc122689587" class="anchor"><span id="_Toc206560077" class="anchor"><span id="_Toc206560162" class="anchor"><span id="_Toc206560395" class="anchor"><span id="_Toc206560505" class="anchor"><span id="_Toc208137534" class="anchor"><span id="_Toc208830644" class="anchor"><span id="_Toc371666024" class="anchor"><span id="_Toc376785400" class="anchor"></span></span></span></span></span></span></span></span></span></span>第四章 系统详细设计
=========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================

系统详细设计在系统架构的基础上对系统功能和结构的细化。根据系统架构，自上而下整个系统被划分成若干层，每一层又被划分成不同的功能模块。系统的业务层被划分成若干独立的功能模块，而系统的功能层又被细分，划分成了小的独立模块。系统详细设计包括代码设计、数据结构和数据库设计、输出输入/人机界面设计、处理过程设计等。

<span id="_Toc376785401" class="anchor"><span id="_Toc208830634" class="anchor"><span id="_Toc371666014" class="anchor"><span id="_Toc206479403" class="anchor"><span id="_Toc122689573" class="anchor"><span id="_Toc206560063" class="anchor"><span id="_Toc206560151" class="anchor"><span id="_Toc206560388" class="anchor"><span id="_Toc206560498" class="anchor"><span id="_Toc208137527" class="anchor"><span id="_Toc206560078" class="anchor"><span id="_Toc206560163" class="anchor"><span id="_Toc206560396" class="anchor"><span id="_Toc206560506" class="anchor"><span id="_Toc208137535" class="anchor"><span id="_Toc208830645" class="anchor"><span id="_Toc371666025" class="anchor"></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span>4.1代码设计
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

代码是客观实体或属性的一种表示符号。在管理信息系统中，代码是人与计算机的共同语言，起着沟通人与计算机的作用。采用代码，可以使数据表达标准化，简化程序设计，加快输入，减少出错，便于计算机处理（记录、检索、排序等），节省存储空间，提高处理速度。代码有很多种类，可按以下两种方式分类。

-   按文字种类分:数字代码、字母代码、数字字母混合码。

-   按功能划分:顺序码、层次码、助记码、合成码等。

在本系统中要用到大量信息元素的编码，代码设计是该系统设计的一项重要的基础工作，对于提高系统的标准化及可扩展性和维护性具有重要意义，下面是本系统主要信息元素的代码设计。

4.2 系统数据库设计
------------------

### <span id="_Toc208830635" class="anchor"><span id="_Toc371666015" class="anchor"><span id="_Toc376785403" class="anchor"></span></span></span>4.2.1 ER图

根据以上各节对系统所做的需求分析、系统设计，规划出仓库管理系统平台的实体关系E-R图。实体关系E-R图是用来描述宴体之间关系的图表，构成E-R图的基本要素是实体型、属性和联系，其表示方法为：

实体型：用矩形表示，矩形框内标注实体名。

属性：用椭圆形表示，并用无向边将其与相应的实体连接起来。

联系：用菱形表示，菱形框内标注联系名，并月无向边分别与有关实体连接起来，同时在无向边旁标上联系的类型（1：l、l:n或m:n）。

<embed src="./media/image6.png" width="346" height="140" />

图4.2.1-1管理员信息实体E-R图

<embed src="./media/image7.png" width="245" height="178" />

图4.2.1-2员工部门信息实体E-R图

<embed src="./media/image8.png" width="422" height="243" />

图4.2.1-3员工信息实体E-R图

<embed src="./media/image9.png" width="360" height="268" />

图4.2.1-4仓库信息实体E-R图

<embed src="./media/image10.png" width="477" height="238" />

图4.2.1-5出/入库信息实体E-R图

<embed src="./media/image11.png" width="489" height="298" />

图4.2.1-6往来单位信息实体E-R图

<embed src="./media/image12.png" width="464" height="310" />

图4.2.1-7入库单信息实体E-R图

<embed src="./media/image13.png" width="464" height="312" />

图4.2.1-8出库单信息实体E-R图

<embed src="./media/image14.png" width="391" height="278" />

图4.2.1-9调拨单信息实体E-R图

<embed src="./media/image15.png" width="390" height="294" />

图4.2.1-10盘点单信息实体E-R图

<embed src="./media/image16.png" width="553" height="295" />

图4.2.1-11货品信息实体E-R图

<embed src="./media/image17.png" width="164" height="230" />

图4.2.1-12计量单位信息实体E-R图

<embed src="./media/image18.png" width="247" height="144" /> <embed src="./media/image19.png" width="262" height="147" />

图4.2.1-12货品分类信息实体E-R图

<embed src="./media/image20.png" width="552" height="537" />

图4.2.1-13仓库管理系统实体联系图

### <span id="_Toc206479404" class="anchor"><span id="_Toc122689574" class="anchor"><span id="_Toc206560064" class="anchor"><span id="_Toc206560152" class="anchor"><span id="_Toc206560389" class="anchor"><span id="_Toc206560499" class="anchor"><span id="_Toc208137528" class="anchor"><span id="_Toc208830636" class="anchor"><span id="_Toc371666016" class="anchor"><span id="_Toc376785404" class="anchor"></span></span></span></span></span></span></span></span></span></span>4.2.2 概念数据模型-CDM

<img src="./media/image21.png" width="552" height="497" />

图4.2.2-1仓库管理系统概念数据模型图

### <span id="_Toc376785405" class="anchor"><span id="_Toc206479413" class="anchor"><span id="_Toc122689583" class="anchor"><span id="_Toc206560073" class="anchor"><span id="_Toc206560158" class="anchor"><span id="_Toc206560394" class="anchor"><span id="_Toc206560504" class="anchor"><span id="_Toc208137533" class="anchor"><span id="_Toc208830637" class="anchor"><span id="_Toc371666017" class="anchor"></span></span></span></span></span></span></span></span></span></span>4.2.3 物理数据模型-PDM

<img src="./media/image22.png" width="552" height="525" />

图4.2.3-1仓库管理系统物理数据模型图

### 4.2.4 面向对象模型-OOM

<img src="./media/image23.png" width="553" height="525" />

图4.2.4-1仓库管理系统面向对象模型图

### 4.2.5 系统数据表设计

<span id="_Toc206479414" class="anchor"><span id="_Toc122689584" class="anchor"><span id="_Toc206560074" class="anchor"><span id="_Toc206560159" class="anchor"></span></span></span></span>由于篇幅所限，仅列几个关键的表出来。

1.操作员表

<img src="./media/image24.png" width="576" height="144" />

2.货品类别表

<img src="./media/image25.png" width="576" height="97" />

3.货品信息表

<img src="./media/image26.png" width="576" height="325" />

4.员工信息表

<img src="./media/image27.png" width="576" height="154" />

5.部门信息表

<img src="./media/image28.png" width="576" height="97" />

6.往来公司信息表

<img src="./media/image29.png" width="576" height="193" />

<img src="./media/image30.png" width="576" height="95" />

7.仓库信息表

<img src="./media/image31.png" width="576" height="136" />

8.仓库库存表

<img src="./media/image32.png" width="576" height="59" />

9.计量单位信息表

<img src="./media/image33.png" width="576" height="58" />

10.货品分类信息表<span id="货品信息分类信息表" class="anchor"></span>

<img src="./media/image34.png" width="576" height="77" />

11.出入库信息表

<img src="./media/image35.png" width="576" height="174" />

12.库存调拨信息表

<img src="./media/image36.png" width="576" height="175" />

13.库存盘点信息表

<img src="./media/image37.png" width="576" height="136" />

14.货品出入库记录表

<img src="./media/image38.png" width="576" height="136" />

15.仓库货品库存信息表

<img src="./media/image32.png" width="576" height="59" />

<span id="_Toc206479418" class="anchor"><span id="_Toc122689588" class="anchor"><span id="_Toc206560079" class="anchor"><span id="_Toc206560164" class="anchor"><span id="_Toc206560397" class="anchor"><span id="_Toc206560507" class="anchor"><span id="_Toc208137536" class="anchor"><span id="_Toc208830653" class="anchor"><span id="_Toc371666033" class="anchor"></span></span></span></span></span></span></span></span></span>
第五章 概要设计
=======================================================================================================================================================================================================================================================================================================================================================================================================================================

<span id="_Toc206479420" class="anchor"><span id="_Toc122689590" class="anchor"><span id="_Toc206560081" class="anchor"><span id="_Toc206560166" class="anchor"><span id="_Toc206560399" class="anchor"><span id="_Toc206560509" class="anchor"><span id="_Toc208137538" class="anchor"><span id="_Toc208830654" class="anchor"><span id="_Toc371666034" class="anchor"><span id="_Toc376785409" class="anchor"><span id="_Toc206479419" class="anchor"><span id="_Toc122689589" class="anchor"><span id="_Toc206560080" class="anchor"><span id="_Toc206560165" class="anchor"><span id="_Toc206560398" class="anchor"><span id="_Toc206560508" class="anchor"><span id="_Toc208137537" class="anchor"></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span>5.1 主界面设计
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<span id="_Toc208830655" class="anchor"><span id="_Toc371666035" class="anchor"></span></span>**5.1.1 登录界面**

<img src="./media/image39.png" width="576" height="315" />

登录界面左侧为用户信息输入区域，下面为开发信息。

**5.1.1 首页界面**

<img src="./media/image40.png" width="553" height="301" />

5.2 系统设置
------------

<img src="./media/image41.png" width="576" height="308" />

**5.2.1 操作用户设置**

左侧显示操作员列表，右侧显示对应的信息。

**5.2.2 数据备份**

<img src="./media/image42.png" width="518" height="151" />

**5.2.3 数据还原**

<img src="./media/image43.png" width="512" height="97" />

**5.2.3 查看系统日志**

<img src="./media/image44.png" width="354" height="203" />

<span id="_Toc376785411" class="anchor"><span id="_Toc206479421" class="anchor"><span id="_Toc122689591" class="anchor"><span id="_Toc206560082" class="anchor"><span id="_Toc206560167" class="anchor"><span id="_Toc206560400" class="anchor"><span id="_Toc206560510" class="anchor"><span id="_Toc208137539" class="anchor"><span id="_Toc208830656" class="anchor"><span id="_Toc371666036" class="anchor"></span></span></span></span></span></span></span></span></span></span>5.3 货品管理
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**5.3.1 货品分类管理**

<img src="./media/image45.png" width="441" height="227" />

**5.3.2 货品信息管理**

<img src="./media/image46.png" width="576" height="202" />

上面设置查询界面，下面显示操作结果。

**5.3.3 添加货品**

<img src="./media/image47.png" width="576" height="324" />

**5.3.4 计量单位管理**

<img src="./media/image48.png" width="265" height="198" />

5.4 基本管理
------------

**5.4.1 往来单位管理**

<img src="./media/image49.png" width="576" height="318" />

**5.4.2 部门信息管理**

<img src="./media/image50.png" width="576" height="214" />

**5.4.3 员工信息管理**

<img src="./media/image51.png" width="576" height="319" />

**5.4.4 仓库信息管理**

<img src="./media/image52.png" width="576" height="187" />

**5.4.5 出入库类别管理**

<img src="./media/image53.png" width="576" height="265" />

5.5 出入库管理
--------------

**5.5.1 货品入库**

<img src="./media/image54.png" width="576" height="348" />

**5.5.2 货品出库**

<img src="./media/image55.png" width="576" height="364" />

**5.5.3 出入库明细**

<img src="./media/image56.png" width="576" height="331" />

**5.5.4 出入库查询**

<img src="./media/image57.png" width="576" height="374" />

5.6 库存管理
------------

**5.6.1 库存调拨**

<img src="./media/image58.png" width="576" height="426" />

**5.6.2 库存盘点**

<img src="./media/image59.png" width="576" height="403" />

**5.6.3 库存查询**

<img src="./media/image60.png" width="576" height="352" />
