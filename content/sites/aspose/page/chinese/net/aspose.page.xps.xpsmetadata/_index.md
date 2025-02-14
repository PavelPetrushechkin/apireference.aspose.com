---
title: Aspose.Page.XPS.XpsMetadata
second_title: Aspose.Page for .NET API 参考
description: 的 Aspose.Page.Xps.Xps元数据命名空间提供了描述 XPS 文档元数据的类
type: docs
weight: 100
url: /zh/net/aspose.page.xps.xpsmetadata/
---
的 **Aspose.Page.Xps.Xps元数据**命名空间提供了描述 XPS 文档元数据的类。

## 课程

| 班级 | 描述 |
| --- | --- |
| [Collate](./collate) | 的基类[`DocumentCollate`](../aspose.page.xps.xpsmetadata/documentcollate)和[`JobCollateAllDocuments`](../aspose.page.xps.xpsmetadata/jobcollatealldocuments)特征类. |
| [CompositePrintTicketElement](./compositeprintticketelement) | 可能是复合打印模式元素（即包含其他元素）的类的基类。 |
| [DecimalValue](./decimalvalue) | 在 PrintTicket 文档中封装 Decimal 值的类。 |
| [DocumentBannerSheet](./documentbannersheet) | 描述要为特定文档输出的标题页。横幅应在 default 上输出[`PageMediaSize`](../aspose.page.xps.xpsmetadata/pagemediasize)并使用默认值[`PageMediaType`](../aspose.page.xps.xpsmetadata/pagemediatype).横幅应该 也与工作的其余部分隔离。这意味着任何精加工或加工选项（例如 [`DocumentDuplex`](../aspose.page.xps.xpsmetadata/documentduplex),[`DocumentStaple`](../aspose.page.xps.xpsmetadata/documentstaple)， 或者[`DocumentBinding`](../aspose.page.xps.xpsmetadata/documentbinding)) 不应包括标题页。标题页可能会或可能不会与作业的其余部分隔离。 这意味着任何作业完成或处理选项都可能包括文档标题页。 标题页应作为文档的第一页出现。 https ://docs.microsoft.com/en-us/windows/win32/printdocs/documentbannersheet |
| [DocumentBannerSheetSource](./documentbannersheetsource) | 指定自定义横幅表的来源。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentbannersheetsource |
| [DocumentBinding](./documentbinding) | 描述绑定方法。每个文档单独绑定。 DocumentBinding 和 JobBindAllDocuments 互斥。 由驱动程序确定关键字之间的约束处理。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentbinding |
| [DocumentBindingGutter](./documentbindinggutter) | 指定装订边距的宽度。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentbindinggutter |
| [DocumentCollate](./documentcollate) | 描述输出的整理特性。每个单独文档中的所有页面都进行了整理。 DocumentCollate 和 JobCollateAlldocuments 是互斥的。 这两个关键字还是只实现其中一个关键字的行为和实现留给驱动程序。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentcollate |
| [DocumentCopiesAllPages](./documentcopiesallpages) | 指定文档的副本数。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentcopiesallpages |
| [DocumentCoverBack](./documentcoverback) | 描述背面（结尾）封面。每份文件都有一张单独的纸。 封面应该打印在[`PageMediaSize`](../aspose.page.xps.xpsmetadata/pagemediasize)和[`PageMediaType`](../aspose.page.xps.xpsmetadata/pagemediatype) 用于文档的最后一页。封面应该集成到加工选项 中（如[`DocumentDuplex`](../aspose.page.xps.xpsmetadata/documentduplex),[`DocumentNUp`](../aspose.page.xps.xpsmetadata/documentnup) 如指定的选项所示。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentcoverback |
| [DocumentCoverBackSource](./documentcoverbacksource) | 指定自定义封底的来源。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentcoverbacksource |
| [DocumentCoverFront](./documentcoverfront) | 描述前（开始）封面。每份文件都有一张单独的纸。 封面应该打印在[`PageMediaSize`](../aspose.page.xps.xpsmetadata/pagemediasize)和[`PageMediaType`](../aspose.page.xps.xpsmetadata/pagemediatype) 用于文档的第一页。封面应该集成到加工选项 中（如[`DocumentDuplex`](../aspose.page.xps.xpsmetadata/documentduplex),[`DocumentNUp`](../aspose.page.xps.xpsmetadata/documentnup) ) 如指定的选项所示。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentcoverfront |
| [DocumentCoverFrontSource](./documentcoverfrontsource) | 指定自定义封面的来源。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentcoverfrontsource |
| [DocumentDuplex](./documentduplex) | 描述输出的双工特性。双面功能允许在介质的两面进行 for 打印。每个文档单独进行双工。 DocumentDuplex 和 JobDuplexAllDocumentsContiguously 是互斥的。 由驱动程序确定这些关键字之间的约束处理。 https://docs.microsoft.com/en-us/windows/win32/printdocs/ documentduplex |
| [DocumentHolePunch](./documentholepunch) | 描述输出的打孔特性。每个文件单独打孔。 [`JobHolePunch`](../aspose.page.xps.xpsmetadata/jobholepunch)和[`DocumentHolePunch`](../aspose.page.xps.xpsmetadata/documentholepunch)关键字是互斥的。 不应在 PrintTicket 或 Print Capabilities 文档中同时指定两者。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentholepunch |
| [DocumentID](./documentid) | 指定文档的唯一 ID。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentid |
| [DocumentImpositionColor](./documentimpositioncolor) | 标有指定命名颜色的应用程序内容必须出现在所有分色上。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentimpositioncolor |
| [DocumentInputBin](./documentinputbin) | 描述设备中安装的输入 bin 或设备支持的 bin 的完整列表。 [`JobInputBin`](../aspose.page.xps.xpsmetadata/jobinputbin),[`DocumentInputBin`](../aspose.page.xps.xpsmetadata/documentinputbin) ， 和[`PageInputBin`](../aspose.page.xps.xpsmetadata/pageinputbin) 关键字是互斥的。两者不应在 PrintTicket 或 Print Capabilities 文档中同时指定。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentinputbin |
| [DocumentName](./documentname) | 指定文档的描述性名称。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentname |
| [DocumentNUp](./documentnup) | 将多个逻辑页面的输出和格式描述到单个物理表。 每个文档单独编译。和[`JobNUpAllDocumentsContiguously`](../aspose.page.xps.xpsmetadata/jobnupalldocumentscontiguously) 是互斥的。由驱动程序决定这些关键字之间的约束处理。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentnup |
| [DocumentOutputBin](./documentoutputbin) | 描述设备支持的 bin 的完整列表。允许基于每个文档指定 output bin。这[`JobOutputBin`](../aspose.page.xps.xpsmetadata/joboutputbin),[`DocumentOutputBin`](../aspose.page.xps.xpsmetadata/documentoutputbin)和 [`PageOutputBin`](../aspose.page.xps.xpsmetadata/pageoutputbin)关键字是互斥的，只有一个应该在 PrintTicket 或 Print Capabilities 文档中指定。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentoutputbin |
| [DocumentPageRanges](./documentpageranges) | 以页面为单位描述文档的输出范围。参数值必须符合以下结构： - PageRangeText：“PageRange”或“PageRange,PageRange” - PageRange：“PageNumber”或“PageNumber-PageNumber” - PageNumber：1到N，其中N是文档中的页面。如果 PageNumber &gt; N，则 PageNumber = N. 字符串中的空白应被忽略。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentpageranges |
| [DocumentPrintTicket](./documentprintticket) | 封装文档级打印票的类。 |
| [DocumentRollCut](./documentrollcut) | 描述卷纸的切割方法。每个文档单独处理。 指定的选项描述了不同的滚切方法。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentrollcut |
| [DocumentSeparatorSheet](./documentseparatorsheet) | 描述文档的分隔页用法。 分隔页应出现在输出中，如下面指定的选项所示。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentseparatorsheet |
| [DocumentStaple](./documentstaple) | 描述输出的装订特性。每个文档单独装订。 [`JobStapleAllDocuments`](../aspose.page.xps.xpsmetadata/jobstaplealldocuments)和[`DocumentStaple`](../aspose.page.xps.xpsmetadata/documentstaple)关键字是互斥的。 由驱动程序来确定这些关键字之间的约束处理。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documentstaple |
| [DocumentURI](./documenturi) | 指定文档的统一资源标识符 (URI)。 https://docs.microsoft.com/en-us/windows/win32/printdocs/documenturi |
| [Duplex](./duplex) | 的基类[`JobDuplexAllDocumentsContiguously`](../aspose.page.xps.xpsmetadata/jobduplexalldocumentscontiguously)和[`DocumentDuplex`](../aspose.page.xps.xpsmetadata/documentduplex)特征类. |
| [Feature](./feature) | 封装通用打印模式特征的类。 所有模式定义特征的基类。 A元素包含完整的列表[`Option`](../aspose.page.xps.xpsmetadata/option)和[`Property`](../aspose.page.xps.xpsmetadata/property) 完全描述设备属性、作业格式设置或其他相关特征的元素。 https://docs.microsoft.com/en-us/windows/win32/printdocs/feature |
| [HolePunch](./holepunch) | 的基类[`JobHolePunch`](../aspose.page.xps.xpsmetadata/jobholepunch)和[`DocumentHolePunch`](../aspose.page.xps.xpsmetadata/documentholepunch)特征类. |
| [IDProperty](./idproperty) | 的基类[`JobID`](../aspose.page.xps.xpsmetadata/jobid)和[`DocumentID`](../aspose.page.xps.xpsmetadata/documentid)属性类. |
| [InputBin](./inputbin) | 的基类[`JobInputBin`](../aspose.page.xps.xpsmetadata/jobinputbin),[`DocumentInputBin`](../aspose.page.xps.xpsmetadata/documentinputbin) 和[`PageInputBin`](../aspose.page.xps.xpsmetadata/pageinputbin)特征类. |
| [IntegerParameterInit](./integerparameterinit) | 所有整数参数初始化器的基类。 |
| [IntegerValue](./integervalue) | 在 PrintTicket 文档中封装 Integer 值的类。 |
| [JobAccountingSheet](./jobaccountingsheet) | 描述要为作业输出的会计表。会计单应该在default 上输出[`PageMediaSize`](../aspose.page.xps.xpsmetadata/pagemediasize)并使用默认值[`PageMediaType`](../aspose.page.xps.xpsmetadata/pagemediatype).会计工作表应该 to 与工作的其余部分隔离开来。这意味着任何精加工或加工选项（例如 ,， 或者 ) 不应包括会计表。 会计表可以作为作业的第一页或最后一页出现，由实施者自行决定。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobaccountingsheet |
| [JobBindAllDocuments](./jobbindalldocuments) | 描述绑定方法。作业中的所有文档都绑定在一起。 [`JobBindAllDocuments`](../aspose.page.xps.xpsmetadata/jobbindalldocuments)和[`DocumentBinding`](../aspose.page.xps.xpsmetadata/documentbinding)是互斥的。 由驱动程序来确定这些关键字之间的约束处理。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobbindalldocuments |
| [JobBindAllDocumentsGutter](./jobbindalldocumentsgutter) | 指定装订边距的宽度。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobbindalldocumentsgutter |
| [JobCollateAllDocuments](./jobcollatealldocuments) | 描述输出的整理特性。每个单独作业中的所有文档都经过整理。 [`DocumentCollate`](../aspose.page.xps.xpsmetadata/documentcollate)和[`JobCollateAllDocuments`](../aspose.page.xps.xpsmetadata/jobcollatealldocuments)是互斥的。 是否实现这两个关键字或仅一个关键字的行为和实现由驱动程序决定。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobcollatealldocuments |
| [JobComment](./jobcomment) | 指定与作业关联的注释。示例：“完成后请送到 1234 房间”。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobcomment |
| [JobCopiesAllDocuments](./jobcopiesalldocuments) | 指定作业的副本数。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobcopiesalldocuments |
| [JobDeviceLanguage](./jobdevicelanguage) | 描述支持从驱动程序向物理设备发送数据的设备语言。 这通常称为“页面描述语言”。此关键字定义驱动程序和物理设备支持的页面描述 语言。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobdevicelanguage |
| [JobDigitalSignatureProcessing](./jobdigitalsignatureprocessing) | 描述为整个作业配置数字签名处理。 仅适用于包含数字签名的内容。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobdigitalsignatureprocessing |
| [JobDuplexAllDocumentsContiguously](./jobduplexalldocumentscontiguously) | 描述输出的双工特性。双面功能允许在介质的 两面打印。作业中的所有文档连续双面打印在一起。 [`JobDuplexAllDocumentsContiguously`](../aspose.page.xps.xpsmetadata/jobduplexalldocumentscontiguously)和[`DocumentDuplex`](../aspose.page.xps.xpsmetadata/documentduplex)是互斥的。 由驱动程序来确定这些关键字之间的约束处理。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobduplexalldocumentscontiguously |
| [JobErrorSheet](./joberrorsheet) | 描述错误表输出。整个作业将有一个错误表。错误 sheet 应该默认输出[`PageMediaSize`](../aspose.page.xps.xpsmetadata/pagemediasize)并使用默认值[`PageMediaType`](../aspose.page.xps.xpsmetadata/pagemediatype). 错误表应与作业的其余部分隔离开来。这意味着任何精加工 or 处理选项（例如,， 或者) 不应包含错误表。错误表应作为作业的最后一页出现。 https://docs.microsoft.com/en-us/windows/win32/printdocs/joberrorsheet |
| [JobErrorSheetSource](./joberrorsheetsource) | 指定自定义错误表的来源。 https://docs.microsoft.com/en-us/windows/win32/printdocs/joberrorsheetsource |
| [JobHolePunch](./jobholepunch) | 描述输出的打孔特性。所有文件都打孔在一起。 [`JobHolePunch`](../aspose.page.xps.xpsmetadata/jobholepunch)和[`DocumentHolePunch`](../aspose.page.xps.xpsmetadata/documentholepunch)关键字是互斥的。 不应在 PrintTicket 或 Print Capabilities 文档中同时指定两者。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobholepunch |
| [JobID](./jobid) | 指定作业的唯一 ID。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobid |
| [JobInputBin](./jobinputbin) | 描述设备中安装的输入箱或设备支持的箱的完整列表。 允许基于每个作业指定输入箱。这[`JobInputBin`](../aspose.page.xps.xpsmetadata/jobinputbin),[`DocumentInputBin`](../aspose.page.xps.xpsmetadata/documentinputbin), 和[`PageInputBin`](../aspose.page.xps.xpsmetadata/pageinputbin)关键字是互斥的。两者不应在 PrintTicket 或 Print Capabilities 文档中同时指定 。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobinputbin |
| [JobName](./jobname) | 指定作业的描述性名称。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobname |
| [JobNUpAllDocumentsContiguously](./jobnupalldocumentscontiguously) | 将多个逻辑页面的输出描述到单个物理表。 job 中的所有文档都是连续编译的。[`JobNUpAllDocumentsContiguously`](../aspose.page.xps.xpsmetadata/jobnupalldocumentscontiguously)和[`DocumentNUp`](../aspose.page.xps.xpsmetadata/documentnup) 是互斥的。由驱动程序来确定这些关键字之间的约束处理。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobnupalldocumentscontiguously |
| [JobOptimalDestinationColorProfile](./joboptimaldestinationcolorprofile) | 指定给定当前设备配置的最佳颜色配置文件。 https://docs.microsoft.com/en-us/windows/win32/printdocs/joboptimaldestinationcolorprofile |
| [JobOutputBin](./joboutputbin) | 描述设备中安装的出纸盒或设备支持的出纸盒的完整列表。 [`JobOutputBin`](../aspose.page.xps.xpsmetadata/joboutputbin),[`DocumentOutputBin`](../aspose.page.xps.xpsmetadata/documentoutputbin)和[`PageOutputBin`](../aspose.page.xps.xpsmetadata/pageoutputbin)关键字 是互斥的，只有一个应在 PrintTicket 或打印功能文档中指定。 https://docs.microsoft.com/en-us/windows/win32/printdocs/joboutputbin |
| [JobOutputOptimization](./joboutputoptimization) | 描述作业处理，旨在优化指定选项所指示的特定使用场景的输出。 https://docs.microsoft.com/en-us/windows/win32/printdocs/joboutputoptimization |
| [JobPageOrder](./jobpageorder) | 定义输出的物理页面顺序。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobpageorder |
| [JobPrimaryBannerSheet](./jobprimarybannersheet) | 描述要为作业输出的标题页。横幅应在 default 上输出[`PageMediaSize`](../aspose.page.xps.xpsmetadata/pagemediasize)并使用默认值[`PageMediaType`](../aspose.page.xps.xpsmetadata/pagemediatype).横幅应该 与工作的其余部分隔离开来。这意味着任何精加工或加工选项（例如 [`JobDuplexAllDocumentsContiguously`](../aspose.page.xps.xpsmetadata/jobduplexalldocumentscontiguously),[`JobStapleAllDocuments`](../aspose.page.xps.xpsmetadata/jobstaplealldocuments)， 或者[`JobBindAllDocuments`](../aspose.page.xps.xpsmetadata/jobbindalldocuments) ) 不应包括标题页。标题页应作为作业的第一页出现。 |
| [JobPrimaryBannerSheetSource](./jobprimarybannersheetsource) | 指定作业的主要自定义横幅表的来源。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobprimarybannersheetsource |
| [JobPrimaryCoverBack](./jobprimarycoverback) | 描述背面（结尾）封面。每个作业都有一个单独的主页。 封面应该打印在[`PageMediaSize`](../aspose.page.xps.xpsmetadata/pagemediasize)和[`PageMediaType`](../aspose.page.xps.xpsmetadata/pagemediatype) 用于作业的最后一页。封面应该集成到加工选项 中（如[`JobDuplexAllDocumentsContiguously`](../aspose.page.xps.xpsmetadata/jobduplexalldocumentscontiguously),[`JobNUpAllDocumentsContiguously`](../aspose.page.xps.xpsmetadata/jobnupalldocumentscontiguously)) 由指定的选项指示。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobprimarycoverback |
| [JobPrimaryCoverBackSource](./jobprimarycoverbacksource) | 指定作业的自定义封底主表的来源。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobprimarycoverbacksource |
| [JobPrimaryCoverFront](./jobprimarycoverfront) | 描述前（开始）封面。整个作业将只有一张主纸。 封面应打印在[`PageMediaSize`](../aspose.page.xps.xpsmetadata/pagemediasize)和[`PageMediaType`](../aspose.page.xps.xpsmetadata/pagemediatype) 用于作业的第一页。封面应该集成到加工选项 中（如[`JobDuplexAllDocumentsContiguously`](../aspose.page.xps.xpsmetadata/jobduplexalldocumentscontiguously),[`JobNUpAllDocumentsContiguously`](../aspose.page.xps.xpsmetadata/jobnupalldocumentscontiguously)) 由指定的选项指示。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobprimarycoverfront |
| [JobPrimaryCoverFrontSource](./jobprimarycoverfrontsource) | 指定作业的自定义封面主页的来源。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobprimarycoverfrontsource |
| [JobPrintTicket](./jobprintticket) | 封装作业级打印票的类。 |
| [JobRollCutAtEndOfJob](./jobrollcutatendofjob) | 描述卷纸的切割方法。卷应在作业结束时切割。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobrollcutatendofjob |
| [JobStapleAllDocuments](./jobstaplealldocuments) | 描述输出的装订特性。作业中的所有文档都装订在一起。 [`JobStapleAllDocuments`](../aspose.page.xps.xpsmetadata/jobstaplealldocuments)和[`DocumentStaple`](../aspose.page.xps.xpsmetadata/documentstaple)关键字是互斥的。 由驱动程序确定这些关键字之间的约束处理。 https://docs.microsoft.com/en-us/windows/win32/printdocs/jobstaplealldocuments |
| [JobURI](./joburi) | 指定文档的统一资源标识符 (URI)。 https://docs.microsoft.com/en-us/windows/win32/printdocs/joburi |
| [NameProperty](./nameproperty) | 的基类[`JobName`](../aspose.page.xps.xpsmetadata/jobname)和[`DocumentName`](../aspose.page.xps.xpsmetadata/documentname)属性类. |
| [NUp](./nup) | 的基类[`JobNUpAllDocumentsContiguously`](../aspose.page.xps.xpsmetadata/jobnupalldocumentscontiguously)和[`DocumentNUp`](../aspose.page.xps.xpsmetadata/documentnup) 要素类。 |
| [Option](./option) | 实现普通 PrintTicket 的类. 所有模式定义选项的基类。 选项元素包含所有[`Property`](../aspose.page.xps.xpsmetadata/property)和 [`ScoredProperty`](../aspose.page.xps.xpsmetadata/scoredproperty)与此选项关联的元素。 https://docs.microsoft.com/en-us/windows/win32/printdocs/option |
| [OutputBin](./outputbin) | 的基类[`JobOutputBin`](../aspose.page.xps.xpsmetadata/joboutputbin),[`DocumentOutputBin`](../aspose.page.xps.xpsmetadata/documentoutputbin)和[`PageOutputBin`](../aspose.page.xps.xpsmetadata/pageoutputbin) 要素类。 |
| [PageBlackGenerationProcessing](./pageblackgenerationprocessing) | 指定 CMYK 分色的黑色生成行为。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pageblackgenerationprocessing |
| [PageBlackGenerationProcessingBlackInkLimit](./pageblackgenerationprocessingblackinklimit) | 标有指定命名颜色的应用程序内容必须出现在所有分色上。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pageblackgenerationprocessingblackinklimit |
| [PageBlackGenerationProcessingGrayComponentReplacementExtent](./pageblackgenerationprocessinggraycomponentreplacementextent) | 描述 GCR 应用的超出中性色（到彩色）的范围。 0% = 统一组件替换，100% = 灰色组件替换。 https://docs.microsoft.com/en-us/windows/win32/printdocs /pageblackgenerationprocessinggraycomponentreplacementextent |
| [PageBlackGenerationProcessingGrayComponentReplacementLevel](./pageblackgenerationprocessinggraycomponentreplacementlevel) | 指定要执行的灰色组件替换的百分比。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pageblackgenerationprocessinggraycomponentreplacementlevel |
| [PageBlackGenerationProcessingGrayComponentReplacementStart](./pageblackgenerationprocessinggraycomponentreplacementstart) | 描述 GCR 应该开始的“突出显示到阴影”范围内的点（100% 最暗的阴影）。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pageblackgenerationprocessinggraycomponentreplacementstart |
| [PageBlackGenerationProcessingTotalInkCoverageLimit](./pageblackgenerationprocessingtotalinkcoveragelimit) | 指定图像中任何位置的四种墨水覆盖率的最大允许总和。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pageblackgenerationprocessingtotalinkcoveragelimit |
| [PageBlackGenerationProcessingUnderColorAdditionLevel](./pageblackgenerationprocessingundercoloradditionlevel) | 描述在暗中性和近中性区域中添加到 GCR/UCR 已生成区域的彩色墨水量（以灰色分量比率表示） “BlackInkLimit”（或 UCAStart，如果指定）。 https://docs.microsoft .com/en-us/windows/win32/printdocs/pageblackgenerationprocessingundercoloradditionlevel |
| [PageBlackGenerationProcessingUnderColorAdditionStart](./pageblackgenerationprocessingundercoloradditionstart) | 描述将应用 UCA 的阴影级别。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pageblackgenerationprocessingundercoloradditionstart |
| [PageBlendColorSpace](./pageblendcolorspace) | 描述应该用于混合操作的色彩空间。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pageblendcolorspace |
| [PageBlendColorSpaceICCProfileURI](./pageblendcolorspaceiccprofileuri) | 指定对 ICC 配置文件的相对 URI 引用，该配置文件定义应该用于混合的颜色空间。 &lt;Uri&gt; 是相对于包根目录的绝对部分名称。 https://docs.microsoft.com/en-us /windows/win32/printdocs/pageblendcolorspaceiccprofileuri |
| [PageBorderless](./pageborderless) | 描述何时应将图像内容打印到介质的物理边缘。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pageborderless |
| [PageColorManagement](./pagecolormanagement) | 为当前页面配置颜色管理。 这在 SHIM 中被认为是自动的 - DM_ICMMethod 添加系统。 描述应该执行颜色管理的组件（即驱动程序）。 https://docs.microsoft.com/en-us/windows /win32/printdocs/pagecolormanagement |
| [PageCopies](./pagecopies) | 指定页面的副本数。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagecopies |
| [PageDestinationColorProfile](./pagedestinationcolorprofile) | 定义目标颜色配置文件的特征。 描述应用程序或驱动程序是否选择要使用的目标颜色配置文件。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagedestinationcolorprofile |
| [PageDestinationColorProfileEmbedded](./pagedestinationcolorprofileembedded) | 指定嵌入的目标颜色配置文件。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagedestinationcolorprofileembedded |
| [PageDestinationColorProfileURI](./pagedestinationcolorprofileuri) | 指定对 XPS 文档中包含的 ICC 配置文件的相对 URI 引用。 此选项的处理取决于 PageDeviceColorSpaceUsage 功能的设置。 假定使用该配置文件的所有元素都已在适当的设备颜色空间中， 并且不会在驱动程序或设备中进行颜色管理。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagedestinationcolorprofileuri |
| [PageDeviceColorSpaceProfileURI](./pagedevicecolorspaceprofileuri) | 将包根的相对 URI 指定到 XPS 文档中包含的 ICC 配置文件。 此选项的处理取决于 PageDeviceColorSpaceUsage 功能的设置。 假定使用该配置文件的所有元素都已采用适当的设备颜色空间， 并且不会在驱动程序或设备中进行颜色管理。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagedevicecolorspaceprofileuri |
| [PageDeviceColorSpaceUsage](./pagedevicecolorspaceusage) | 与[`PageDeviceColorSpaceProfileURI`](../aspose.page.xps.xpsmetadata/pagedevicecolorspaceprofileuri)参数，此参数定义 在设备颜色空间中呈现的元素的呈现行为。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagedevicecolorspaceusage |
| [PageDeviceFontSubstitution](./pagedevicefontsubstitution) | 描述设备字体替换的启用/禁用状态。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagedevicefontsubstitution |
| [PageForceFrontSide](./pageforcefrontside) | 强制输出显示在介质表的前面。与每侧具有不同 表面的介质表相关。在此功能干扰处理选项的情况下（例如 [`DocumentDuplex`](../aspose.page.xps.xpsmetadata/documentduplex) ),优先应用该功能的特定 页面。 |
| [PageICMRenderingIntent](./pageicmrenderingintent) | 描述 ICC v2 规范定义的渲染意图。 如果图像或图形元素具有指定渲染意图的嵌入式配置文件 ，则应忽略此值。 https://docs.microsoft.com/en-us/ windows/win32/printdocs/pageicmrenderingintent |
| [PageImageableSize](./pageimageablesize) | 描述用于布局和渲染的图像画布。这将根据 报告[`PageMediaSize`](../aspose.page.xps.xpsmetadata/pagemediasize)和[`PageOrientation`](../aspose.page.xps.xpsmetadata/pageorientation). https://docs.microsoft.com/en-us/windows/win32/printdocs/pageimageablesize |
| [PageInputBin](./pageinputbin) | 描述设备中安装的输入箱或设备支持的箱的完整列表。 允许基于每页指定输入箱。这[`JobInputBin`](../aspose.page.xps.xpsmetadata/jobinputbin),[`DocumentInputBin`](../aspose.page.xps.xpsmetadata/documentinputbin)和 [`PageInputBin`](../aspose.page.xps.xpsmetadata/pageinputbin)关键字是互斥的。两者不应在 PrintTicket 或 Print Capabilities 文档中同时指定 。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pageinputbin |
| [PageMediaColor](./pagemediacolor) | 描述媒体颜色选项和每个选项的特征。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagemediacolor |
| [PageMediaSize](./pagemediasize) | 描述用于输出的物理媒体尺寸。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagemediasize |
| [PageMediaSizeMediaSizeHeight](./pagemediasizemediasizeheight) | 指定尺寸自定义方向option. https://docs.microsoft.com/en-us/windows/win32/printdocs/pagemediasizemediasizeheight |
| [PageMediaSizeMediaSizeWidth](./pagemediasizemediasizewidth) | 指定尺寸自定义方向 option. https://docs.microsoft.com/en-us/windows/win32/printdocs/pagemediasizemediasizewidth |
| [PageMediaSizePSHeight](./pagemediasizepsheight) | 指定页面的高度，平行于进纸方向。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagemediasizepsheight |
| [PageMediaSizePSHeightOffset](./pagemediasizepsheightoffset) | 指定偏移量，平行于进纸方向。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagemediasizepsheightoffset |
| [PageMediaSizePSOrientation](./pagemediasizepsorientation) | 指定相对于进纸方向的方向 direction https://docs.microsoft.com/en-us/windows/win32/printdocs/pagemediasizepsorientation |
| [PageMediaSizePSWidth](./pagemediasizepswidth) | 指定垂直于进纸方向的页面宽度。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagemediasizepswidth |
| [PageMediaSizePSWidthOffset](./pagemediasizepswidthoffset) | 指定垂直于进纸方向的偏移量。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagemediasizepswidthoffset |
| [PageMediaType](./pagemediatype) | 描述选项和每个选项的特点。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagemediatype |
| [PageMirrorImage](./pagemirrorimage) | 描述输出的镜像设置。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagemirrorimage |
| [PageNegativeImage](./pagenegativeimage) | 描述输出的负数设置。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagenegativeimage |
| [PageOrientation](./pageorientation) | 描述物理介质表的方向。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pageorientation |
| [PageOutputBin](./pageoutputbin) | 描述设备支持的 bin 的完整列表。允许在每页的基础上指定出纸槽。 [`JobOutputBin`](../aspose.page.xps.xpsmetadata/joboutputbin),[`DocumentOutputBin`](../aspose.page.xps.xpsmetadata/documentoutputbin)和[`PageOutputBin`](../aspose.page.xps.xpsmetadata/pageoutputbin)关键字 are 互斥 仅应在 PrintTicket 或 Print Capabilities 文档中指定一个。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pageoutputbin |
| [PageOutputColor](./pageoutputcolor) | 描述输出颜色设置的特征。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pageoutputcolor |
| [PageOutputQuality](./pageoutputquality) | 描述输出的负值设置。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pageoutputquality |
| [PagePhotoPrintingIntent](./pagephotoprintingintent) | 表示驱动程序的高级意图以填充照片打印设置。 这些设置处理用户在打印照片时可能指定的预期输出质量。 https://docs.microsoft.com/en-us/windows /win32/printdocs/pagephotoprintingintent |
| [PagePoster](./pageposter) | 描述单个页面到多个物理介质表的输出。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pageposter |
| [PagePrintTicket](./pageprintticket) | 封装页面级打印票的类。 |
| [PageResolution](./pageresolution) | 将打印输出的页面分辨率定义为定性值或每英寸点数，或两者兼而有之。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pageresolution |
| [PageScaling](./pagescaling) | 描述输出的缩放特性。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagescaling |
| [PageScalingOffsetHeight](./pagescalingoffsetheight) | 指定缩放偏移量自定义缩放的方向。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagescalingoffsetheight |
| [PageScalingOffsetWidth](./pagescalingoffsetwidth) | 指定缩放偏移量自定义缩放的方向。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagescalingoffsetwidth |
| [PageScalingScale](./pagescalingscale) | 指定自定义正方形缩放的比例因子。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagescalingscale |
| [PageScalingScaleHeight](./pagescalingscaleheight) | 指定在自定义缩放的方向。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagescalingscaleheight |
| [PageScalingScaleWidth](./pagescalingscalewidth) | 指定在自定义缩放的方向。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagescalingscalewidth |
| [PageSourceColorProfile](./pagesourcecolorprofile) | 定义源颜色配置文件的特征。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagesourcecolorprofile |
| [PageSourceColorProfileEmbedded](./pagesourcecolorprofileembedded) | 指定嵌入的源颜色配置文件。 |
| [PageSourceColorProfileURI](./pagesourcecolorprofileuri) | 指定颜色配置文件的来源。 |
| [PageTrueTypeFontMode](./pagetruetypefontmode) | 描述要使用的 TrueType 字体处理方法。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagetruetypefontmode |
| [PageWatermark](./pagewatermark) | 描述输出的水印设置和水印特性。水印将 应用于逻辑页面，而不是物理页面。例如，如果[`DocumentDuplex`](../aspose.page.xps.xpsmetadata/documentduplex)已启用， 将出现一个水印每张纸上的页面。如果[`DocumentDuplex`](../aspose.page.xps.xpsmetadata/documentduplex), =2，那么每张纸会有2个水印。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagewatermark |
| [PageWatermarkOriginHeight](./pagewatermarkoriginheight) | 指定相对于水印原点的水印原点. https://docs.microsoft.com/en-us/windows/win32/printdocs/pagewatermarkoriginheight |
| [PageWatermarkOriginWidth](./pagewatermarkoriginwidth) | 指定相对于水印原点的水印原点 . https://docs.microsoft.com/en-us/windows/win32/printdocs/pagewatermarkoriginwidth |
| [PageWatermarkTextAngle](./pagewatermarktextangle) | 指定水印文本相对于方向。 角度以逆时针方向测量。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagewatermarktextangle |
| [PageWatermarkTextColor](./pagewatermarktextcolor) | 定义水印文本的 sRGB 颜色。格式为 ARGB：#AARRGGBB. https://docs.microsoft.com/en-us/windows/win32/printdocs/pagewatermarktextcolor |
| [PageWatermarkTextFontSize](./pagewatermarktextfontsize) | 定义水印文本的可用字体大小。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagewatermarktextfontsize |
| [PageWatermarkTextText](./pagewatermarktexttext) | 指定水印的文本。 https://docs.microsoft.com/en-us/windows/win32/printdocs/pagewatermarktexttext |
| [PageWatermarkTransparency](./pagewatermarktransparency) | 指定水印的透明度。完全不透明的值为 0. https://docs.microsoft.com/en-us/windows/win32/printdocs/pagewatermarktransparency |
| [ParameterInit](./parameterinit) | 实现通用 PrintTicket 参数初始化程序的类。 所有模式定义的参数初始化程序的基类。 定义一个实例的值元素. A element 是 a 引用的目标[`ParameterRef`](../aspose.page.xps.xpsmetadata/parameterref)element. https://docs.microsoft.com/en-us/windows/win32/printdocs/parameterinit |
| [ParameterRef](./parameterref) | 实现通用 PrintTicket 参数引用的类。 A元素定义对 a 的引用[`ParameterInit`](../aspose.page.xps.xpsmetadata/parameterinit)元素. A[`ScoredProperty`](../aspose.page.xps.xpsmetadata/scoredproperty)包含 ParameterRef 元素的元素没有 显式设置[`Value`](../aspose.page.xps.xpsmetadata/value)元素。相反，[`ScoredProperty`](../aspose.page.xps.xpsmetadata/scoredproperty) element 从[`ParameterInit`](../aspose.page.xps.xpsmetadata/parameterinit) 引用的元素element. https://docs.microsoft.com/en-us/windows/win32/printdocs/parameterref |
| [PrintTicket](./printticket) | 实现任何范围的通用 PrintTicket 的类。 作业级、文档级和页面级打印票的基类。 Aelement 是 PrintTicket 文档的根元素。 A元素包含输出作业所需的所有作业格式信息。 https://docs.microsoft.com/en-us/windows/win32/printdocs/printticket |
| [PrintTicketElement](./printticketelement) | 可能是打印模式元素的类的基类。 |
| [Property](./property) | 实现普通 PrintTicket 的类 . 所有模式定义属性的基类。 A元素声明设备、作业格式或其他相关属性 ，其名称由其名称属性给出。一个[`Value`](../aspose.page.xps.xpsmetadata/value)元素用于分配 一个值给. 一个可能很复杂，可能包含多个子属性。 子属性也表示为元素. https://docs.microsoft.com/en-us/windows/win32/printdocs/property |
| [QNameValue](./qnamevalue) | 在 PrintTicket 文档中封装 QName 值的类。 |
| [RollCut](./rollcut) | 的基类[`JobRollCutAtEndOfJob`](../aspose.page.xps.xpsmetadata/jobrollcutatendofjob)和[`DocumentRollCut`](../aspose.page.xps.xpsmetadata/documentrollcut)特征类. |
| [ScoredProperty](./scoredproperty) | 实现普通 PrintTicket 的类. 所有模式定义的评分属性的基类。 A元素声明了 an 固有的属性[`Option`](../aspose.page.xps.xpsmetadata/option)定义。在评估 请求的接近程度时，应比较此类属性[`Option`](../aspose.page.xps.xpsmetadata/option)匹配设备支持的[`Option`](../aspose.page.xps.xpsmetadata/option). https://docs.microsoft.com/en-us/windows/win32/printdocs/scoredproperty |
| [SelectionType](./selectiontype) | SelectionType PrintTicket 属性的便利类。 |
| [Staple](./staple) | 的基类[`JobStapleAllDocuments`](../aspose.page.xps.xpsmetadata/jobstaplealldocuments)和[`DocumentStaple`](../aspose.page.xps.xpsmetadata/documentstaple)特征类. |
| [StringParameterInit](./stringparameterinit) | 所有字符串参数初始化器的基类。 |
| [StringValue](./stringvalue) | 在 PrintTicket 文档中封装 String 值的类。 |
| [URIProperty](./uriproperty) | 的基类[`JobURI`](../aspose.page.xps.xpsmetadata/joburi)和[`DocumentURI`](../aspose.page.xps.xpsmetadata/documenturi)属性类. |
| [Value](./value) | 封装了一个基类[`Property`](../aspose.page.xps.xpsmetadata/property)或一个[`ScoredProperty`](../aspose.page.xps.xpsmetadata/scoredproperty) PrintTicket 文档中的值。 值元素将文字与类型相关联。 https://docs.microsoft.com/en-us/windows/win32/printdocs/value |
## 接口

| 界面 | 描述 |
| --- | --- |
| [IDocumentPrintTicketItem](./idocumentprintticketitem) | 带文件前缀的打印票项接口。 |
| [IFeatureItem](./ifeatureitem) | 可能是打印模式的类的基本接口[`Feature`](../aspose.page.xps.xpsmetadata/feature)项目. |
| [IJobPrintTicketItem](./ijobprintticketitem) | 作业前缀打印票项接口。 |
| [IOptionItem](./ioptionitem) | 可能是 Print Schema 的类的接口[`Option`](../aspose.page.xps.xpsmetadata/option)项目. |
| [IPagePrintTicketItem](./ipageprintticketitem) | 页前缀打印票项接口。 |
| [IPrintTicketElementChild](./iprintticketelementchild) | 任何打印模式元素的子元素的基本接口。 |
| [IPrintTicketItem](./iprintticketitem) | 类的基接口[`PrintTicket`](../aspose.page.xps.xpsmetadata/printticket)根元素 items. 它也是定义范围前缀的接口的基本接口。 |
| [IPropertyItem](./ipropertyitem) | 可能是 PrintTicket 的类的基本接口[`Property`](../aspose.page.xps.xpsmetadata/property)项目. |
| [IScoredPropertyItem](./iscoredpropertyitem) | 可能是 PrintTicket 的类的基本接口[`ScoredProperty`](../aspose.page.xps.xpsmetadata/scoredproperty)项目. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
