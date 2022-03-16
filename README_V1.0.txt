README V1.0

1. 项目的名称和简介
开源项目的名称为“RIOS Patent Classification”（RIOS实验室专利分类，简称为RPC）,该开源RPC文档主要针对处理器的功能模块进行技术分类。RPC目前分为四个层级，第一层级目前包括R01（Micro-architecture）和R02（Instruction Set Architecture, ISA）。其中，R01在第二层级进一步包括：Core, Cache, Co-processor, Interconnect, Debugger等等。第二层级的Core在第三层级进一步包括：Fetch Unit, Branch Predictor, Decode Unit, Hazard Handling, Dispatch Unit, Issue Unit等等，以此类推。在RPC分类中，几乎所有的专利都能分到第三层级，少部分的专利能分到第四层级。例如，第三层级的Fetch Unit能进一步分成第四层级：Instruction Prefetch和Instruction Buffer。
2. 项目背景
为什么要有上述RIOS实验室的处理器技术分类RPC？
首先，由于现有的IPC（International Patent Classification, 国际专利分类）和CPC（Cooperative Patent Classification, 合作专利分类）分类号涵盖了生物、化学、政治、经济、物理等多个方面，技术划分过于宽泛，对于计算机处理器的划分起始于G（物理），没有专门针对处理器各个功能模块的技术细节进行划分。RIOS实验室聚焦于处理器的开发和设计，根据技术实现的功能模块，来划分处理器技术类别，更能体现专业性和方便研发人员检索某一特定处理器功能模块的专利。
    其次，专利审查局为了方便对专利进行技术审查，会将专利从多个技术角度来进行划分，使用多个IPC和CPC分类号对专利进行分类，但没有重要性的权重，主要技术类别被次要技术类别掩盖。在分析专利布局时，可能会存在数据的失真。
最后，RIOS实验室的处理器技术分类不排斥IPC和CPC分类号，结合RIOS实验室的处理器技术分类RPC、IPC分类号、和CPC分类号，能更好地帮助技术人员理解处理器各个功能模块的专利技术。
3. RPC分类的来源
    RIOS实验室的处理器技术分类RPC来源于伯克利EECS（Electrical Engineering and Computer Sciences）课程，课程网址参见https://eecs.berkeley.edu/academics/courses。
4. 许可证
对于本开源RPC文档的内容，目前暂时采用 3-clause BSD License  （3条款BSD许可证）进行授权，3条款BSD许可证原文参见网址：https://opensource.org/licenses/BSD-3-Clause。
需要说明的是，RIOS实验室目前正在研究属于自己的开源许可证，当RIOS实验室自己的开源许可证完成后，将用新的许可证替换现有的3条款BSD许可证。
5. 授予的权利
（1）传播权 
在任何媒介或格式下复制并分发本开源RPC文档。如转载至您的网站，或将其印刷后分发。
（2）改编权 
对本开源RPC文档进行修改或依据本开源RPC文档进行再创作。如对本开源RPC文档进行修改或编辑，并重新发布。
（3）商业利用权
您可以基于任何目的或环境使用本创作，即使运用于商业性用途。但是，当您在商业性用途中销售本开源RPC文档的电子或印刷拷贝时，您必须明确声明这些拷贝副本并非来自本开源RPC文档的原始版权作者。
6. 限制条件
（1）版权声明 
如果对本开源RPC文档进行修改并传播，您必须提供版权声明，明确说明本开源RPC文档的原始版权作者，并提供本开源RPC文档的原始链接。例如，分发时在文档的介绍性描述或前页、头版中提供本开源RPC文档的原始链接，并明确指出本开源RPC文档可在上述链接处获取。
同时，除非原始版权作者许可，您不得明示或暗示您的使用行为或商业行为，来自于原始版权作者的授权，或原始版权作者已为您的使用行为或商业行为提供保证。
（2）修改后的文档以相同许可证共享
如果您对本开源RPC文档进行了修改或再创作，您必须采用与本开源RPC文档相同的许可证来分发您的创作。
（3）不得增加额外限制条件
您不能增设任何额外的法律限制条件或技术限制条件，以限制他人进行本开源RPC文档采用的许可证允许的行为，并不得限制他人根据本开源RPC文档获得的权利。






