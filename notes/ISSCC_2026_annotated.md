# ISSCC 2026 转写注释报告

> 说明：按“原文一段 / 注释一段”整理。原文基于你提供的 PDF 转写，注释以技术逻辑、产业含义、指标口径为主，不做无依据扩写。

## 1. ISSCC 2026 的会议定位

**原文**  
There are three major semiconductor conferences each year, IEDM, VLSI and finally ISSCC. We have covered the former two in great detail over the past few years. Today, we finally complete the trinity with our roundup on ISSCC 2026.  
每年有三场主要的半导体会议：IEDM、VLSI 以及最后的 ISSCC。在过去的几年里，我们已经详细报道了前两场。今天，随着我们对 ISSCC 2026 的综述，我们终于完成了这一“三位一体”的报道。  

**注释**  
这段在给 ISSCC 定位。半导体三大会里：IEDM 更偏器件与工艺前沿，VLSI 介于工艺与设计之间，ISSCC 更偏电路实现、芯片集成和实测结果。也就是说，ISSCC 的价值不只是“提出方向”，而是“拿出 silicon 结果”。对产业判断来说，这类会议信号通常比纯概念型论文更接近量产现实。

**原文**  
Compared to IEDM and VLSI, ISSCC has a much bigger focus on integration and circuits. Almost every paper comes with some form of circuit diagram, together with clear measurements and data.  
与 IEDM 和 VLSI 相比，ISSCC 更加侧重于集成和电路。几乎每篇论文都附带某种形式的电路图，以及明确的测量结果和数据。  

**注释**  
这句话的重点是“integration and circuits”以及“clear measurements and data”。换句话说，ISSCC 不是只谈器件可行性，而是谈架构、电路、实现路径和测出来的性能。对投资或产业跟踪来说，这类内容更适合拿来判断技术成熟度、成本路径和量产节奏。

## 2. 今年 ISSCC 与市场趋势的关系

**原文**  
In past years, ISSCC findings have been hit or miss when it comes to industry impact. This year was different, a significant number of papers and presentations were directly relevant to market trends. Topics covered range from the latest advancements in HBM4, LPDDR6, GDDR7, and NAND, to co-packaged optics, advanced die-to-die interfaces, and advanced processors from the likes of MediaTek, AMD, Nvidia, and Microsoft.  
在往年，ISSCC 的研究成果在行业影响力方面表现参差不齐。但今年有所不同，大量的论文和演讲都与市场趋势直接相关。涵盖的主题从 HBM4、LPDDR6、GDDR7 和 NAND 的最新进展，到共封装光学（CPO）、先进的片间（die-to-die）接口，以及来自 MediaTek、AMD、Nvidia 和 Microsoft 等公司的先进处理器。  

**注释**  
这段的核心判断是：2026 年 ISSCC 的议题与现实产业需求高度重合。HBM4、LPDDR6、GDDR7、CPO、die-to-die 这些都不是远期概念，而是 AI 服务器、边缘设备、高带宽封装和先进互连的直接痛点。意味着半导体技术周期正在从“探索式创新”转向“AI 驱动下的工程兑现”。

**原文**  
In this roundup, we will cover major categories such as Memory, Optical Networking, High-Speed Electrical Interconnects, Processors.  
在此次综述中，我们将涵盖存储器、光网络、高速电学互连以及处理器等主要类别。  

**注释**  
这个分类本身就说明了产业主线：不是单点芯片创新，而是从存储、互连、光学到处理器的整栈协同。AI 产业链现在真正的瓶颈不在单一算力芯片，而在于系统级吞吐、功耗和封装互连。

## 3. 存储成为今年的核心主线

**原文**  
One key theme that caught our attention at this year’s ISSCC was memory, including Samsung HBM4, Samsung and SK Hynix LPDDR6, and SK Hynix GDDR7. Other than DRAM, logic-based SRAM and MRAM also piqued our interest.  
在今年的 ISSCC 上，引起我们关注的一个关键主题是存储器，包括三星 HBM4、三星和 SK Hynix 的 LPDDR6，以及 SK Hynix 的 GDDR7。除了 DRAM 之外，基于逻辑的 SRAM 和 MRAM 也引起了我们的兴趣。  

**注释**  
这句话直接点出今年最重要的主线是 memory。原因很简单：AI 负载越来越受限于带宽、容量、延迟和功耗，而不是只受限于裸算力。HBM 面向训练与高端推理，LPDDR 面向移动端与低功耗场景，GDDR 面向图形和部分推理加速场景。不同存储路线同时推进，说明需求端正在分层分化。

## 4. Samsung HBM4 的产业意义

**原文**  
Samsung was the only one among the top three memory vendors to present a technical paper on HBM4. Before ISSCC, we noted in our Accelerator & HBM model that Samsung had made great improvements in their HBM4 generation over their HBM3E. The data presented at ISSCC confirmed our analysis, with Samsung posting best-in-class performance - we have also detailed this development months ago, in a model update note.  
三星是三大存储器厂商中唯一一家提交关于 HBM4 技术论文的公司。在 ISSCC 之前，我们在 Accelerator & HBM 模型中就已指出，三星在 HBM4 代际上较其 HBM3E 有了巨大改进。ISSCC 上展示的数据证实了我们的分析，三星展示了同类最佳的性能——我们在几个月前的模型更新说明中也详细阐述了这一进展。  

**注释**  
这里的重点不是“只有三星发论文”本身，而是三星愿意拿出更多技术细节，说明它在 HBM4 上有更强的展示意愿和竞争诉求。对于过去在 HBM 上落后于 SK 海力士的三星来说，这意味着它正在尝试通过技术代际切换完成追赶甚至局部反超。

**原文**  
The technical details presented at ISSCC, combined with industry chatter we have gathered, clearly demonstrate that Samsung’s HBM4 is competitive with its peers. Notably, it can meet the pin speed required for Rubin while staying below 1V. While Samsung still lags SK Hynix in terms of reliability and stability, the company has made meaningful progress in closing the gap on the technology front and could challenge SK Hynix’s dominance in HBM. Their 1c-based HBM4 paired with an SF4 logic base die appears to deliver stronger performance in pin speed.  
在 ISSCC 上展示的技术细节，结合我们收集到的行业传闻，清楚地表明三星的 HBM4 与同行相比具有竞争力。值得注意的是，它可以在保持低于 1V 电压的同时，满足 Rubin 所需的引脚速度。虽然三星在可靠性和稳定性方面仍落后于 SK 海力士，但该公司在缩小技术差距方面取得了实质性进展，并可能挑战 SK 海力士在 HBM 领域的霸主地位。他们基于 1c 工艺的 HBM4 搭配 SF4 逻辑基础底片，似乎在引脚速度上表现出更强的性能。  

**注释**  
这一段有三个关键点：第一，Samsung 的 HBM4 已经不是落后产品，而是具备竞争力；第二，低于 1V 仍能满足高 pin speed，说明其功耗效率改进很明显；第三，性能提升主要来自 1c DRAM 核心堆叠加 SF4 逻辑 base die 的组合。也就是说，Samsung 的追赶不是靠简单堆频，而是靠工艺拆分和底层架构升级。

## 5. HBM4 的实物规格与结构变化

**原文**  
Samsung demonstrated a 36 GB, 12-high HBM4 stack featuring 2048 IO pins and 3.3 TB/s of bandwidth, built using 6th-generation 10nm-class (1c) DRAM core dies paired with an SF4 logic base die.  
三星展示了一个 36 GB、12 层堆叠的 HBM4 样品，具有 2048 个 IO 引脚和 3.3 TB/s 的带宽，采用第六代 10 纳米级（1c）DRAM 核心颗粒与 SF4 逻辑基础底片制造而成。  

**注释**  
这组数据的意义很直接：36GB、12Hi、2048 IO、3.3TB/s，说明 Samsung 已经把 HBM4 做到高容量、高堆叠和高带宽并存。对 AI 加速卡而言，这直接对应更高参数模型、更高 batch、更大吞吐。特别是 2048 IO 和 3.3TB/s，说明带宽提升已经不是小修小补，而是代际跃迁。

**原文**  
The most obvious architectural change from HBM3E to HBM4 is the process technology split between the core DRAM dies and the base die. HBM4 uses the DRAM process node only for the core die while the base die is manufactured with an advanced logic node unlike previous generations of HBM that used the same process for both.  
从 HBM3E 到 HBM4 最明显的架构变化是核心 DRAM 堆栈与基础底座之间的工艺技术分离。HBM4 仅在核心堆栈上使用 DRAM 工艺节点，而基础底座则采用先进的逻辑工艺节点制造，这与以往几代 HBM 在两者上使用相同工艺的做法不同。  

**注释**  
这是 HBM4 最关键的代际变化之一。过去 base die 也跑 DRAM 工艺，逻辑能力受限。现在把 base die 切到先进逻辑工艺，相当于把 HBM 的“控制和接口层”升级成更像逻辑芯片。这样可以显著提升 IO、时序控制、测试能力和功耗效率。产业上看，这意味着 HBM 从“堆叠 DRAM”进一步进化成“存算接口高度复杂的系统级器件”。

## 6. SF4 base die 带来的性能和功耗收益

**原文**  
The key architectural challenge arises as AI workloads demand higher bandwidth and faster data rates from HBM. By moving the base die to the SF4 logic process, Samsung enables higher operating speeds and lower power consumption. The operating voltage (VDDQ) fell 32%, from 1.1V in HBM3E to 0.75V in HBM4. A logic-based base die provides higher transistor density, smaller device dimensions, and better area efficiency due to smaller transistors and larger metal-layer stack availability as compared to a base die fabricated on a DRAM process. This helps Samsung’s HBM4 achieve — and significantly surpass — JEDEC’s HBM4 standard.  
随着 AI 工作负载对 HBM 提出更高的带宽和更大数据速率的需求，关键的架构挑战也随之而来。通过将基础底座迁移至 SF4 逻辑工艺，三星实现了更高的运行速度和更低的功耗。其工作电压（VDDQ）从 HBM3E 的 1.1V 下降了 32%，在 HBM4 中降至 0.75V。与基于 DRAM 工艺制造的基础底座相比，基于逻辑工艺的基础底座提供了更高的晶体管密度、更小的器件尺寸，并且由于晶体管更小以及可用的金属层堆栈更多，其面积效率也更高。这有助于三星的 HBM4 达到并显著超越 JEDEC 的 HBM4 标准。  

**注释**  
这里最重要的数据是 VDDQ 从 1.1V 降到 0.75V，降幅 32%。这不是小优化，而是非常实质性的功耗改进。对于 HBM 来说，接口功耗极其关键，因为总带宽越高，IO 功耗越容易变成瓶颈。base die 逻辑化之后，Samsung 实际上是在用更先进的逻辑制程去解决高带宽内存的系统瓶颈。

## 7. ABB 与 TSV 数量提升的作用

**原文**  
Combined with adaptive body-bias (ABB) control, which mitigates process variation across stacked core dies, the doubled TSV counts further improve timing margin. Together, Samsung’s paper claimed that the ABB and the 4× higher TSV count allow their HBM4 to achieve operating speeds up to 13 Gb/s per pin.  
结合自适应体偏置（ABB）控制，该技术可减轻堆叠核心芯片间的工艺偏差，翻倍的 TSV 数量进一步提升了时序裕量。三星的论文称，ABB 与 4 倍的 TSV 数量共同作用，使其 HBM4 能够实现高达每引脚 13 Gb/s 的运行速度。  

**注释**  
HBM 堆叠越高，工艺差异和时序偏差越难压住。ABB 是在校正不同 die 之间的差异，更多 TSV 则是在强化信号和时序路径。两者叠加，本质是在为更高 pin speed 扩大 timing margin。13Gb/s/pin 这个结果说明 Samsung 不是只在 nominal 条件下快，而是在时序控制层面做了更多工程投入。

## 8. 更强性能背后的成本与良率代价

**原文**  
The improvement brought by the SF4 base die and 1c DRAM core dies comes with a trade-off. Samsung’s choice of SF4 for the logic base die comes at a higher cost compared with competing approaches. SK Hynix is adopting TSMC’s N12 logic process for their HBM4 base die, while Micron relies on their internal CMOS base-die technology, both of which are lower-cost options than the near leading-edge SF4 node.  
SF4 基础底片和 1c DRAM 核心底片带来的性能提升也伴随着权衡。三星选择 SF4 作为逻辑基础底片，其成本高于竞争对手的方案。SK Hynix 的 HBM4 基础底片采用了 TSMC 的 N12 逻辑工艺，而 Micron 则依赖其内部的 CMOS 基础底片技术，这两者的成本都低于接近领先节点的 SF4。  

**注释**  
这段讲的是 trade-off。Samsung 走的是更激进的性能路线，因此 base die 成本更高。对手则更多是在性能与成本之间取平衡。换句话说，Samsung 在 HBM4 上更像是在用先进工艺买性能，而不是优先买利润率。

**原文**  
The 1c front-end manufacturing process has proved challenging for Samsung throughout 2025. Front-end yields for the 1c node were only around 50% last year, although they have been gradually improving over time. The lower yield poses a risk for their HBM4 margins.  
1c 前端制造工艺在整个 2025 年对三星来说都极具挑战。去年 1c 节点的前端良率仅为 50% 左右，尽管随着时间的推移正在逐步改善。较低的良率对其 HBM4 的利润率构成了风险。  

**注释**  
这里要看两个层面：技术上，Samsung 做出来了；经营上，能不能赚到钱还不一定。1c 前段良率只有约 50%，意味着 wafer 成本和最终有效产出之间存在很大损耗。即便技术性能先进，若良率爬坡慢，HBM4 也可能出现“产品强、利润弱”的局面。

## 9. tCCDR 问题与自动校准

**原文**  
Another key issue in HBM to address is tCCDR, the minimum interval required between consecutive READ commands issued across different stack IDs (SID). For AI workloads that rely heavily on parallel memory access across many channels, tCCDR directly impacts achievable memory throughput.  
HBM 另一个需要解决的关键问题是 tCCDR，即在不同堆栈 ID 之间发出连续读取命令所需的最小间隔。对于严重依赖多通道并行内存访问的 AI 工作负载，tCCDR 直接影响可实现的内存吞吐量。  

**注释**  
tCCDR 本质上不是一个边角参数，而是决定多通道并行读能否高效展开的关键时序约束。AI 工作负载天生依赖并行访问，如果这个间隔压不下来，理论带宽就难以变成可用吞吐。所以 Samsung 在 HBM4 里重点解决 tCCDR，是很合理的方向。

**原文**  
To address this issue, Samsung introduces a “per-channel TSV RDQS timing auto-calibration scheme.” After power-up, the system measures delay variation across channels using a replica RDQS path that mirrors the timing behavior of the real signal path. A time-to-digital converter (TDC) quantizes the timing differences, which are then compensated for using delay compensation circuits (DCDL) for each channel.  
为了解决这一问题，三星推出了一种“每通道 TSV RDQS 定时自动校准方案”。系统在通电后，会利用一个镜像真实信号路径定时行为的副本 RDQS 路径，来测量各通道间的延迟变化。时间数字转换器会对定时差异进行量化，随后通过每个通道的延迟补偿电路进行补偿。  

**注释**  
这是典型的工程化解决方案：不是试图消灭所有物理差异，而是在上电后测出来，再逐通道补偿。好处是更现实，也更适合大规模量产。说明 HBM4 的进步不只是工艺升级，还有大量校准和补偿机制在托底。

**原文**  
This scheme alone increased data rates from 7.8 Gb/s to 9.4 Gb/s.  
仅这一方案就将数据速率从 7.8 Gb/s 提升到了 9.4 Gb/s。  

**注释**  
单个校准方案就能带来约 20% 的速率提升，说明此前的主要限制之一确实时序失配，而不是单纯工艺不够。也说明今天高带宽内存的竞争，很多时候不是比谁 cell 更先进，而是比谁在系统时序与校准上做得更深。

## 10. PMBIST 的价值

**原文**  
Another key innovation enabled by the logic base die is Samsung’s Programmable Memory Built-In Self-Test (PMBIST) architecture. PMBIST allows the base die to generate fully programmable memory test patterns while supporting the complete JEDEC row and column command set. In practical terms, this allows engineers to replicate complex real-world memory access patterns and stress the HBM interface under realistic operating conditions.  
逻辑基础底层的另一项关键创新是三星的可编程内存内置自检架构。PMBIST 允许基础底层生成完全可编程的内存测试模式，同时支持完整的 JEDEC 行和列命令集。在实际应用中，这使得工程师能够复制复杂的真实世界内存访问模式，并在真实的运行条件下对 HBM 接口进行压力测试。  

**注释**  
PMBIST 的意义不在“测试”两个字本身，而在“可编程”和“贴近真实系统”。HBM 越复杂，传统固定模式测试越不够用。PMBIST 让 base die 具备更强的测试与 debug 能力，本质上是提升 bring-up、失效定位和量产爬坡效率。

**原文**  
Put simply, PMBIST improves test coverage, debug efficiency, and ultimately production yield as HBM stacks grow more complex and operate at higher speeds.  
简而言之，随着 HBM 堆栈变得日益复杂且运行速度不断提高，PMBIST 提高了测试覆盖率、调试效率，并最终提升了生产良率。  

**注释**  
一句话概括：逻辑 base die 不只是为了更高带宽，也是为了让 HBM 更容易被制造、测试和量产。对产业来说，这一点很重要，因为先进封装时代，能不能测、能不能调、能不能稳定交付，和能不能设计出来一样重要。

## 11. Samsung HBM4 的最终性能结论

**原文**  
Samsung also demonstrated strong pin speed results — their HBM4 is able to hit 11 Gb/s at sub-1V core voltage (VDDC), and up to 13 Gb/s at higher voltages.  
三星也展示了强劲的引脚速度结果——其 HBM4 在低于 1V 的核心电压下能够达到 11 Gb/s，在更高电压下则可达 13 Gb/s。  

**注释**  
这个结果说明 Samsung HBM4 的两个维度都做到了：一是高绝对性能，二是低压下仍有不错表现。前者决定峰值能力，后者决定实用价值。对 AI 服务器来说，后者往往更关键，因为机架级系统真正受限的是功耗与散热。

**原文**  
Samsung’s implementation significantly exceeds the baseline specification of the official JEDEC HBM4 standard, which specifies a maximum data rate of 6.4 Gb/s per pin and about 2 TB/s of bandwidth. Samsung demonstrates more than 2× the JEDEC-standard pin speed, reaching 13 Gb/s per pin and delivering 3.3 TB/s of bandwidth.  
三星的实现方案显著超越了官方 JEDEC HBM4 标准的基准规范，该标准规定的最大引脚数据速率为 6.4 Gb/s，带宽约为 2 TB/s。三星展示了超过 JEDEC 标准两倍的引脚速度，达到每引脚 13 Gb/s，并提供 3.3 TB/s 的带宽。  

**注释**  
这里要注意，JEDEC 标准是底线，不是天花板。Samsung 明显是在证明：先进客户的需求已经远高于标准最低门槛。换句话说，AI 时代的 HBM 正在从“标准驱动”转向“客户定制与领先实现驱动”。

## 12. LPDDR6：从标准升级到架构变化

**原文**  
Samsung presented their LPDDR6 architecture and detailed the power-saving techniques used.  
三星展示了其 LPDDR6 架构，并详细介绍了所采用的节能技术。  

**注释**  
LPDDR6 的重点不是只追求更高速率，更重要的是在高频下仍控制功耗。因为 LPDDR 的主战场是手机、PC、边缘设备、低功耗 AI 终端，功耗效率比极限峰值更关键。

**原文**  
LPDDR6 adopts a 2 sub-channel per die architecture, with 16 banks in each sub-channel. It also features two modes: a normal mode and an efficiency mode. In the efficiency mode, the secondary sub-channel is powered down, and the primary sub-channel controls all 32 banks. However, there is a latency penalty for accessing data in the secondary sub-channel.  
LPDDR6 采用了每颗芯片 2 个子通道的架构，每个子通道包含 16 个 bank。它还具有两种模式：正常模式和效率模式。在效率模式下，次级子通道会断电，由主子通道控制所有 32 个 bank。然而，访问次级子通道中的数据会产生延迟惩罚。  

**注释**  
这段说明 LPDDR6 的方向是：用更细粒度的通道划分换取更好的带宽调度与节能模式。正常模式优先性能，效率模式优先功耗。代价是架构更复杂，而且效率模式下会引入访问延迟惩罚。这本质上是典型的移动内存设计思路：允许一定性能折损，换更好的能效比。

**原文**  
The dual sub-channel architecture also means that there is twice the amount of peripheral circuitry. From the die shots provided by both Samsung and SK Hynix, the penalty is about 5% of the total die area.  
双子通道架构也意味着外围电路的数量增加了一倍。从三星和 SK 海力士提供的芯片照片来看，这一代价约占芯片总面积的 5%。  

**注释**  
这说明 LPDDR6 的升级并不是白来的。双子通道提升了灵活性和功耗管理能力，但面积也要付出代价。5% 听上去不大，但在 DRAM 这种极度吃面积和成本的产品里，已经是很实在的代价。

## 13. Wide-NRZ、Metadata 和 DBI

**原文**  
Unlike GDDR7, which uses PAM3 signaling, LPDDR6 will continue to use NRZ. However, it does not use standard NRZ as the eye would not have sufficient margin. It uses wide NRZ with 12 data (DQ) pins per sub-channel and a burst length of 24 per operation.  
与使用 PAM3 信号传输的 GDDR7 不同，LPDDR6 将继续使用 NRZ。然而，它并未使用标准的 NRZ，因为其眼图将没有足够的余量。它采用了宽位 NRZ，每个子通道拥有 12 个数据引脚，且每次操作的突发长度为 24。  

**注释**  
这段的含义是：LPDDR6 没有像 GDDR7 那样激进地走到 PAM3，而是在信号可靠性、复杂度和功耗之间做折中，采用 wide-NRZ。这说明 LPDDR6 的优先级仍然是移动端可实现性，而不是单纯追最高每 pin 速率。

**原文**  
The remaining 32 bits are split into 2 use cases, 16 for metadata like ECC, and 16 for Data Bus Inversion (DBI).  
剩余的 32 位被分为两种用途：16 位用于 ECC 等元数据，另外 16 位用于数据总线倒置。  

**注释**  
这句话点明了 LPDDR6 的有效带宽不能只看裸 pin speed。因为传输里不全是纯数据，还包含 metadata 和 DBI。也就是说，宣传速率和真实可用带宽之间存在折算关系。

**原文**  
DBI is a power-saving and signal integrity mechanism.  
DBI 是一种节能和信号完整性机制。  

**注释**  
DBI 的本质是降低同时翻转位数，减轻供电噪声和信号完整性压力。这是典型的高频 IO 工程手段。频率越高，这种机制的收益越明显。

## 14. LPDDR6 的有效带宽与功耗优化

**原文**  
To calculate the effective bandwidth, you must account for these metadata and DBI bits like so: Bandwidth = Data Rate × Width (24 b) × Data (32 b) / Packet (36 b). For 12.8 Gb/s, you get 34.1 GB/s, and for 14.4 Gb/s, you get 38.4 GB/s.  
要计算有效带宽，你必须像这样考虑这些元数据和 DBI 位：带宽 = 数据速率 × 宽度 (24 b) × 数据 (32 b) / 数据包 (36 b)。对于 12.8 Gb/s，你可以获得 34.1 GB/s；而对于 14.4 Gb/s，你可以获得 38.4 GB/s。  

**注释**  
这段很重要，因为它提醒不能直接把 14.4Gb/s 理解成等比例的纯数据吞吐。真实有效带宽需要扣除协议和控制开销。对比不同厂商 LPDDR6 时，必须统一口径，否则容易高估实际性能。

**原文**  
By carefully choosing which peripheral logic is using which power domain, read power has been reduced by 27% and write power reduced by 22%.  
通过精心选择外围逻辑所使用的功率域，读取功耗降低了 27%，写入功耗降低了 22%。  

**注释**  
这表明 Samsung LPDDR6 的改进不只是架构层面的，也包括非常细的电源域划分优化。读功耗降低 27%、写功耗降低 22%，在移动内存里已经是相当可观的优化幅度。

## 15. 低速空闲场景与 RDL 设计

**原文**  
LPDDR is primarily used at low data rates of 3.2 Gb/s and below when idling. Samsung focused heavily on saving power at these lower data rates through careful use of the voltage domains, reducing both standby and read/write power consumption.  
LPDDR 主要在 3.2 Gb/s 及以下的低数据速率空闲状态下使用。三星通过谨慎使用电压域，重点致力于降低这些低数据速率下的功耗，从而减少了待机以及读/写功耗。  

**注释**  
这句话很关键。很多人只盯满速功耗，但 LPDDR 大量时间其实在低速或空闲态。真正影响续航和系统能耗的，往往正是这些低速状态。所以 Samsung 把优化重点放在 3.2Gb/s 及以下，是符合终端真实使用场景的。

**原文**  
By using a redistribution layer (RDL), Samsung can locate related circuits closer together physically. This shortens critical delay paths and reduces their sensitivity to voltage and temperature variation.  
通过使用重布线层，三星可以将相关电路在物理位置上放置得更近。这缩短了关键延迟路径，并降低了它们对电压和温度变化的敏感度。  

**注释**  
RDL 在这里的价值不是封装概念，而是直接帮助高频时序收敛。电路更近，路径更短，PVT 变化影响更小。这说明 LPDDR6 已经把很多原本属于先进封装或高频 SerDes 的设计方法吸收到移动内存里。

## 16. Samsung 与 SK Hynix LPDDR6 对比

**原文**  
Samsung’s LPDDR6 can reach a data rate of 12.8 Gb/s at 0.97V, and up to 14.4 Gb/s at 1.025V.  
三星的 LPDDR6 在 0.97V 电压下数据传输速率可达 12.8 Gb/s，在 1.025V 下最高可达 14.4 Gb/s。  

**注释**  
Samsung 的 LPDDR6 展示出两个层次：一是 14.4Gb/s 的高端能力，二是低于 1V 时仍然能跑到 12.8Gb/s，说明它在低压效率上有优势。对终端产品来说，后者通常更有商业价值。

**原文**  
SK Hynix unveiled their first 1c DRAM products, both in LPDDR6 and in GDDR7 packages. Their LPDDR6 can operate at a data rate of up to 14.4 Gb/s, 35% faster than the fastest LPDDR5X, and at lower power.  
SK 海力士展示了其首批 1c DRAM 产品，包括 LPDDR6 和 GDDR7 封装。其 LPDDR6 的数据传输速率高达 14.4 Gb/s，比最快的 LPDDR5X 快 35%，且功耗更低。  

**注释**  
SK Hynix 的重点是证明其 1c 节点已经进入可用产品阶段，而且不只做 HBM，也覆盖 LPDDR6、GDDR7。这说明其 DRAM 工艺平台在多个产品线开始共振。

**原文**  
However, they can only reach 10.9 Gb/s at 0.95V as compared to Samsung’s 12.8 Gb/s at 0.97V. This indicates that SK Hynix may have worse power efficiency at lower pin speeds when compared to Samsung.  
然而，在 0.95V 时，SK Hynix 仅能达到 10.9 Gb/s，而 Samsung 在 0.97V 时即可达到 12.8 Gb/s。这表明，与 Samsung 相比，SK Hynix 在较低的引脚速度下功耗效率可能较差。  

**注释**  
两家如果只看峰值，都能到 14.4Gb/s；但若看低压区间，Samsung 更强。说明 Samsung 在 LPDDR6 上的优势可能主要体现在能效，而不一定只是绝对速率。

## 17. SK Hynix GDDR7 的意义

**原文**  
While the LPDDR6 is a generational leap with new memory technology, SK Hynix’s GDDR7 on their 1c process shows an even greater improvement, clocking up to 48 Gb/s at 1.2V/1.2V. Even at only 1.05V/0.9V, it can clock up to 30.3 Gb/s.  
虽然 LPDDR6 是采用新内存技术的代际飞跃，但 SK 海力士基于 1c 工艺的 GDDR7 表现出了更大的进步，在 1.2V/1.2V 电压下频率高达 48 Gb/s。即使在仅为 1.05V/0.9V 的电压下，其速率也能达到 30.3 Gb/s。  

**注释**  
GDDR7 的这组数据说明 1c 节点给高频图形内存带来的改进非常明显。48Gb/s 已经是相当激进的水平，而在较低电压下仍有 30.3Gb/s，说明其信号质量和功耗控制都在提升。对显卡和部分推理加速卡来说，这会是重要方向。

## 18. 总结

**原文**  
One key theme that caught our attention at this year’s ISSCC was memory.  
在今年的 ISSCC 上，引起我们关注的一个关键主题是存储器。  

**注释**  
如果把全文压缩成一句话，就是：AI 时代，存储已经从“配套部件”变成系统主角。HBM4 代表高端 AI 系统对带宽和封装的极限追求，LPDDR6 代表边缘和终端设备对能效和灵活性的追求，GDDR7 则继续向高频率推进。三条线同时进展，说明内存已经是 AI 基础设施里最核心的矛盾之一。
