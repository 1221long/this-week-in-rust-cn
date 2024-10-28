标题：本周Rust 570 
编号：570 日期：2024 - 10 - 23 类别：本周Rust

大家好，欢迎收看另一期的*这周在鲁斯特。*！[Rust](https://www.rust-lang.org/)是一种编程语言，使每个人都能够构建可靠且高效的软件。这是对其进展和社区的每周总结。想提点什么吗？在 [@ 这个星期Rust](https://x.com/ThisWeekInRust)X（以前的 Twitter）或 [@ 这个星期Rust](https://mastodon.social/@thisweekinrust)Mastodon.Social 上标记我们，或者[向我们发送拉取请求](https://github.com/rust-lang/this-week-in-rust)。想参与吗？[我们热爱贡献](https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md)。

 *这周在鲁斯特。*是公开开发的[on GitHub](https://github.com/rust-lang/this-week-in-rust)，档案可以在上[这一周在 rust.org](https://this-week-in-rust.org/)查看。如果你在本周的期刊中发现任何错误，[请提交 PR](https://github.com/rust-lang/this-week-in-rust/pulls)。

想要收件箱中的 Twir 吗？[在这里订阅](https://this-week-in-rust.us11.list-manage.com/subscribe?u=fd84c1c757e02889a9b08d289&id=0ed8b72485)。

## 来自 Rust 社区的更新

<!--

Dear community contributors:
Please read README.md for guidance on submissions.
Each submitted link should be of the form:

* [Title of the Linked Page](https://example.com/my_article)

If you don't know which category to use, feel free to submit a PR anyway
and just ask the editors to select the category.

-->

### 官方的
*  [宣布 Rust 1.8 2.0](https://blog.rust-lang.org/2024/10/17/Rust-1.82.0.html)

### 项目/工具更新
*  [Ratatui 0.29.0](https://ratatui.rs/highlights/v029/)
*  [ZED 扩展的生命：生锈，智慧，WASM](https://zed.dev/blog/zed-decoded-extensions)
*  [Shuttle 的新平台—重新定义后端开发](https://www.shuttle.dev/blog/2024/10/10/shuttle-redefining-backend-development)
*  [HiFiTime 4.0.0 版：时间管理的飞跃](https://nyxspace.com/blog/2024/10/17/hifitime-version-400-a-leap-forward-in-time-management/)
*  [Fjall 2.2 - 现在支持可序列化的快照隔离（多写入器事务）](https://fjall-rs.github.io/post/announcing-fjall-22/)
*  [PG-extras-rs-PostgreSQL 数据库性能洞察](https://github.com/pawurb/pg-extras-rs)

### 观察/想法
*  [Rust 的设计目标应该是关于代码的](https://tmandry.gitlab.io/blog/posts/the-main-thing/)
*  [UnpinCell](https://without.boats/blog/unpin-cell/)
*  [阻塞代码是一种有漏洞的抽象](https://notgull.net/blocking-leaky/)
*  [作为Rust项目贡献者的生活](https://yaah.dev/staying-involved)
*  [RustLS 的性能优于 OpenSSL 和 BoringSSL](https://www.memorysafety.org/blog/rustls-performance-outperforms/)
*  [在 Bevy 中使用 libgdx 纹理图谱](https://rustunit.com/blog/2024/10-21-bevy-libgdx-atlas/)
* [音频] [生产中的Rust - 与康拉德 · 欧文一起](https://corrode.dev/podcast/s03e01-zed/)
* [音频] [异步分配器](https://sdr-podcast.com/episodes/async-allocators/)
* [音频] [PubNub 与斯蒂芬 · 布鲁姆](https://rustacean-station.org/episode/stephen-blum/)

### Rust 演练
*  [揭开 Rust 中对齐和内存布局的神秘面纱](https://garden.christophertee.dev/blogs/Memory-Alignment-and-Layout/Part-1)
*  [在非 Rust 服务器中使用 Rust 以提高性能](https://github.com/pretzelhammer/rust-blog/blob/master/posts/rust-in-non-rust-servers.md)
*  [异步 Rust 分为三个部分](https://jacko.io/async_intro.html)
*  [什么时候应该使用 String vs&amp;str？](https://steveklabnik.com/writing/when-should-i-use-string-vs-str/)
*  [在 Rust WebApps 中使用 Web Workers](https://allwright.io/#/blog/20241016-using-web-workers.md)

### 其他的
*  [创建Rust社区](https://www.understandingrecruitment.com/knowledge-hub/blog/the-rust-review-starting-a-rust-community/)

## 本周板条箱

本周的机箱是[trait-gen](https://crates.io/crates/trait-gen)一个属性宏，它可以为几种类型生成特征实现，而不需要自定义声明性宏、代码重复或总括实现。

谢谢你[卢克 · 彼得森](https://users.rust-lang.org/t/crate-of-the-week/2704/1358)的建议！

[请提交你下周的建议和投票] [提交 _ 板条箱]！

[submit_crate]: https://users.rust-lang.org/t/crate-of-the-week/2704

## 要求测试
RFC 实现的一个重要步骤是让人们对实现进行试验并给出反馈，尤其是在稳定之前。以下 RFC 将从用户测试中受益，然后再继续：

###  [RFCs](https://github.com/rust-lang/rfcs/issues?q=label%3Acall-for-testing)
*  *本周没有发出测试要求。*

###  [Rust](https://github.com/rust-lang/rust/labels/call-for-testing)
*  *本周没有发出测试要求。*

###  [Rustup](https://github.com/rust-lang/rustup/labels/call-for-testing)
*  *本周没有发出测试要求。*

### 板条箱生态系统
* [请求输入： `zerocopy`：你是否需要 `IntoBytes` S 上的 `union` 支持？请称重。] (https：//github.com/google/zerocopy/discussions/1802）

如果你是功能实现者，并希望你的 RFC 出现在上面的列表中，请将新 `call-for-testing` 标签添加到你的 RFC 中，并附上注释，提供测试说明和/或关于功能的哪些方面需要测试的指导。

## 呼吁参与；项目和演讲者

### CFP-项目

一直想为开源项目做贡献，但不知道从哪里开始？每周我们都会重点介绍一些来自 Rust 社区的任务，供你挑选并开始使用！

其中一些任务可能也有可用的导师，请访问任务页面了解更多信息。

*  [Rama—添加“全部拒绝”DNS 解析器](https://github.com/plabayo/rama/issues/329)
*  [Rama—扩展对基于上下文数据的劫持的支持](https://github.com/plabayo/rama/issues/328)
*  [Rama—支持 DNSResolver 的 VEC/Array 实现](https://github.com/plabayo/rama/issues/332)
*  [Rama—支持连接器和解析器中的 IP 模式](https://github.com/plabayo/rama/issues/331)

如果你是 Rust 项目的所有者，并且正在寻找贡献者，请提交任务 [此处] [指南] 或通过[PR to TWiR](https://github.com/rust-lang/this-week-in-rust)或联系[X（前身为 Twitter）](https://x.com/ThisWeekInRust)或[Mastodon](https://mastodon.social/@thisweekinrust)！

[guidelines]:https://github.com/rust-lang/this-week-in-rust?tab=readme-ov-file#call-for-participation-guidelines

### CFP-事件

你是一个新的或有经验的演讲者，想找个地方分享一些很酷的东西吗？本节重点介绍正在计划的活动，并接受提交作为演讲者参加其活动。

 *本周没有要求提交论文或演示文稿。*

如果你是活动组织者，希望扩大活动的影响范围，请通过[PR to TWiR](https://github.com/rust-lang/this-week-in-rust)或提交网站链接 [Mastodon](https://mastodon.social/@thisweekinrust)[X（前身为 Twitter）](https://x.com/ThisWeekInRust)。

## 来自 Rust 项目的更新

[上周已合并] [已合并] 464 个拉取请求

[merged]: https://github.com/search?q=is%3Apr+org%3Arust-lang+is%3Amerged+merged%3A2024-10-15..2024-10-22

* [使 `rustc_abi` 编译再次稳定] (https：//github.com/rust-lang/rust/pull/131997）
* [ `optimize` 应用于除方法/函数/C 之外的事物的属性…] (https：//github.com/rust-lang/rust/pull/131814）
* [ `rust_for_linux: -Zregparm=<N>` x86 命令行标志] (https：//github.com/rust-lang/rust/pull/130432）
* [ `rustc_llvm`：修复扁平 CLI 参数] (https：//github.com/rust-lang/rust/pull/131805）
* [添加 `&pin (mut|const) T` 类型位置糖] (https：//github.com/rust-lang/rust/pull/130635）
*  [为 RTEMS 添加 GetEntropy](https://github.com/rust-lang/rust/pull/131774)
*  [添加了更多要在函数 arg 中删除逗号的场景](https://github.com/rust-lang/rust/pull/126588)
* [允许 `#[deny]` 内部 `#[forbid]` 无操作] (https：//github.com/rust-lang/rust/pull/121560）
*  [允许删除 Dyn 主体](https://github.com/rust-lang/rust/pull/131857)
* [始终为 RISC-V 目标指定 `llvm_abiname`] (https：//github.com/rust-lang/rust/pull/131807）
*  [AutoDiff 上行流 - 酶前端](https://github.com/rust-lang/rust/pull/129458)
*  [将孤立提示从“仅”更改为“..中的任何未覆盖类型”。](https://github.com/rust-lang/rust/pull/128391)
* [检查文件在标记的 `skip-filecheck` 文件中检查指令] (https：//github.com/rust-lang/rust/pull/131927）
* [编译：采用锈蚀分析仪 IMPLS `LayoutCalculatorError`] (https：//github.com/rust-lang/rust/pull/131942）
*  [编译器：具有无效 REPR 的枚举布局出错](https://github.com/rust-lang/rust/pull/131843)
*  [编译器：使用 LLVM 的 COMDAT 支持](https://github.com/rust-lang/rust/pull/131876)
* [继续摆脱 `ty::Const::{try_}eval*`] (https：//github.com/rust-lang/rust/pull/130950）
*  [覆盖率：使计数器创建更加统一地处理节点/边缘计数器](https://github.com/rust-lang/rust/pull/131918)
*  [默认为 OpenHarmony LoongArch 目标上的中等代码模型](https://github.com/rust-lang/rust/pull/131874)
* [填充后 `Cache` 延迟不明确的文档内链接解析] (https：//github.com/rust-lang/rust/pull/131691）
*  [不要在无法运行的地方运行测试](https://github.com/rust-lang/rust/pull/131835)
*  [当不透明保留时，不检查 MIR 验证中的未调整大小目标](https://github.com/rust-lang/rust/pull/130989)
* [不要报告 `on_unimplemented` 负面信息] (https：//github.com/rust-lang/rust/pull/131701）
* [将具有字段错误的 `struct` 嵌套到另一个 `struct` 中时，不报告双方差错误] (https：//github.com/rust-lang/rust/pull/131754）
*  [计算合成异步闭包体的覆盖范围时不要冻结](https://github.com/rust-lang/rust/pull/131802)
* [Don t consider predicate that may hold as impossible in `is_impossible_associated_item`] (https：//github.com/rust-lang/rust/pull/131840）
*  [为 LoongArch Linux 目标启用 X 射线检测](https://github.com/rust-lang/rust/pull/131818)
*  [修复超大元组™的一致性错误](https://github.com/rust-lang/rust/pull/132001)
*  [修复范围误导性字段访问](https://github.com/rust-lang/rust/pull/131537)
* [简洁地处理真/假 `cfg(target(..))`] (https：//github.com/rust-lang/rust/pull/131771）
*  [Implement Edition 2024 符合人体工程学限制](https://github.com/rust-lang/rust/pull/131381)
* [出现 `unsupported_calling_conventions` 硬错误] (https：//github.com/rust-lang/rust/pull/129935）
* [在要执行的 `extern "C"` 帧上生成析构函数] (https：//github.com/rust-lang/rust/pull/129582）
* [使某些浮动方法不稳定 `const fn`] (https：//github.com/rust-lang/rust/pull/130568）
*  [即使使用精确的捕获语法，也要确保外部不透明捕获内部不透明的生存期。](https://github.com/rust-lang/rust/pull/131789)
* [从不为空发射 `vptr`/自动特征] (https：//github.com/rust-lang/rust/pull/131864）
* [注册 `src/tools/unicode-table-generator` 为可运行工具] (https：//github.com/rust-lang/rust/pull/131647）
*  [删除常量指针的无效帮助诊断](https://github.com/rust-lang/rust/pull/127675)
*  [使用返回区指针返回大于 2 个寄存器的值](https://github.com/rust-lang/rust/pull/131211)
*  [为 LoongArch64-Linux- {musl，ohos} 设置对外部数据的间接访问](https://github.com/rust-lang/rust/pull/131583)
*  [尝试改进求解器中涉及别名的错误消息](https://github.com/rust-lang/rust/pull/131699)
*  [对 FFI 中的非详尽警告较少](https://github.com/rust-lang/rust/pull/116863)
* [Miri： `epoll_ctl`：在不受支持的操作码上引发不受支持的错误] (https：//github.com/rust-lang/miri/pull/3982）
*  [Miri：Android：添加了对 prctl 处理线程名称的支持](https://github.com/rust-lang/miri/pull/3899)
* [Miri：改善对和 `f128` 的支持 `f16`] (https：//github.com/rust-lang/miri/pull/3977）
*  [计算默认可见性时添加快速路径](https://github.com/rust-lang/rust/pull/131686)
* [用于 `ThinVec` 谓词义务存储] (https：//github.com/rust-lang/rust/pull/131422）
* [完成稳定 `result_ffi_guarantees`] (https：//github.com/rust-lang/rust/pull/130628）
*  [稳定严格来源和暴露来源的 API](https://github.com/rust-lang/rust/pull/130350)
* [再次稳定 `-Znext-solver=coherence`] (https：//github.com/rust-lang/rust/pull/130654）
* [ `from_ref` 将和 `from_mut` 构造函数添加到 `core::ptr::NonNull`] (https：//github.com/rust-lang/rust/pull/130822）
* [添加 `must_use` 到 `CommandExt::exec`] (https：//github.com/rust-lang/rust/pull/131833）
* [避免在中 `thread_local_inner!` 使用导入] (https：//github.com/rust-lang/rust/pull/131866）
* [标记不稳定 `LazyCell::into_inner` 常数] (https：//github.com/rust-lang/rust/pull/131712）
* [优化 `Box::default` 并 `Arc::default` 就地构造更多类型] (https：//github.com/rust-lang/rust/pull/131460）
*  [优化 str.replace](https://github.com/rust-lang/rust/pull/130223)
* [部分稳定 `const_pin`] (https：//github.com/rust-lang/rust/pull/130136）
* [重构一些 `core::fmt` 宏] (https：//github.com/rust-lang/rust/pull/131730）
* [避免多余的 UB 签入 `IndexRange`] (https：//github.com/rust-lang/rust/pull/131572）
* [Relax a memory order in `once_box`] (https：//github.com/rust-lang/rust/pull/131746）
*  [在 Windows 上加速目录遍历](https://github.com/rust-lang/rust/pull/131972)
*  [STD：UEFI：添加基本环境变量](https://github.com/rust-lang/rust/pull/127462)
*  [UEFI：实现 getcwd 和 chdir](https://github.com/rust-lang/rust/pull/129794)
* [Cargo：Registry：HttpRegistry 在工作仍未完成时提前 `block_until_ready` 返回] (https：//github.com/rust-lang/cargo/pull/14694）
*  [cargo：resolver：使用 rcveciter 进行迭代时避免克隆](https://github.com/rust-lang/cargo/pull/14690)
*  [货物：稳定 MSRV 感知解析器配置](https://github.com/rust-lang/cargo/pull/14639)
*  [rustdoc-JSON-types：引入 rustc-hash 特性](https://github.com/rust-lang/rust/pull/131936)
*  [rustdoc-JSON-types：将简单枚举标记为副本](https://github.com/rust-lang/rust/pull/131976)
*  [RustDoc：从 FXHASH 切换到 SHA256 以进行静态文件哈希](https://github.com/rust-lang/rust/pull/131908)
* [RUSTFMT `for<'a> async` 正确] (https：//github.com/rust-lang/rust/pull/131657）
* [rustfmt： `compile_rustfmt` 重写] (https：//github.com/rust-lang/rustfmt/pull/6275）
*  [rustfmt：将 2024 版本排序算法应用于 MODS](https://github.com/rust-lang/rustfmt/pull/6368)
* [rustfmt：将零参数函数的更改推迟到 `style_edition=2027`] (https：//github.com/rust-lang/rustfmt/pull/6362）
* [clippy：为不必要的生命期有界 `&str` 返回添加 lint] (https：//github.com/rust-lang/rust-clippy/pull/13395）
*  [Clippy：允许在没有 JavaScript 的情况下浏览 Clippy Lints 页面](https://github.com/rust-lang/rust-clippy/pull/13539)
* [clippy：将的 `manual_is_power_of_two` 类别更改为 `pedantic`] (https：//github.com/rust-lang/rust-clippy/pull/13553）
* [clippy：在任何宏调用中停止 linting `manual_bits`] (https：//github.com/rust-lang/rust-clippy/pull/13564）
*  [Rust-Analyzer：在选项中添加 Wrap/Unwrap 返回类型](https://github.com/rust-lang/rust-analyzer/pull/18294)
* [Rust-Analyzer：Clamp `Position::character` to Line Length] (https：//github.com/rust-lang/rust-analyzer/pull/18243）
*  [Rust-Analyzer：不考虑计算为的位置的 match/let/ref！为了分道扬镳，他们也不允许强制。](https://github.com/rust-lang/rust-analyzer/pull/18278)
*  [Rust-Analyzer：更好地完成外部区块](https://github.com/rust-lang/rust-analyzer/pull/18360)
*  [Rust-Analyzer：在范围操作符上转到定义](https://github.com/rust-lang/rust-analyzer/pull/18362)
* [Rust-Analyzer：外部模块中的 `safe_kw` 初始支持] (https：//github.com/rust-lang/rust-analyzer/pull/18350）
*  [Rust-Analyzer：支持 InitializeStopped 设置](https://github.com/rust-lang/rust-analyzer/pull/18359)
*  [Rust-Analyzer：修复未标记 Markdown 的状态栏消息](https://github.com/rust-lang/rust-analyzer/pull/18366)
* [Rust-Analyzer：分类 `safe` 为上下文关键字] (https：//github.com/rust-lang/rust-analyzer/pull/18354）
*  [Rust-Analyzer：修复了 Include 的令牌向下映射失败！输入](https://github.com/rust-lang/rust-analyzer/pull/18361)
*  [Rust-Analyzer：私有项目显示在 FN Body 中模块的完成中](https://github.com/rust-lang/rust-analyzer/pull/18337)

### Rust 编译器性能分类

通过切换到下一代特征解算器（仅用于一致性检查）和简化我们的数据流分析框架，进行了一些整洁的改进。有一些与 PR 126557 相关的二元大小回归（添加 `#[track_caller]` 到和 `VecDeque` 的 `Vec` 分配方法中），我已将其移交给 T-LIBS，以选择是否进一步调查。

分类由**@PNKFelix**完成。修订范围：[5CEB623A.。3E33BDA0](https://perf.rust-lang.org/?start=5ceb623a4abd66e91e7959d25caaf0523f1a7f7c&end=3e33bda0326586a6e1e34d0f5c060ca6d116e6a4&absolute=false&stat=instructions%3Au)

回归 0 例，进步 3 例，混合 6 例；其中 3 个在汇总中，总共进行了 47 次伪影比较

 [完整报告在这里](https://github.com/rust-lang/rustc-perf/blob/81de3d5e2cc599cc49bc11c64f9a5b911f3a83dd/triage/2024-10-21.md)

###  [批准的 RFC](https://github.com/rust-lang/rfcs/commits/master)

Rust的变化随着Rust而来[RFC（征求意见）流程](https://github.com/rust-lang/rfcs#rust-rfcs)。以下是本周批准实施的 RFC：

* [RFC：允许将布尔文字用作 `cfg` 谓词] (https：//github.com/rust-lang/rfcs/pull/3695）

### 最终意见征询期
每周，[the team](https://www.rust-lang.org/team.html)宣布即将做出决定的 RFC 和关键 PR 的“最终意见征询期”。现在发表你的意见。

####  [RFCs](https://github.com/rust-lang/rfcs/labels/final-comment-period)
* [处理：合并] [RFC：让用户控制功能统一](https://github.com/rust-lang/rfcs/pull/3692)
* [处理：合并] [[RFC] 默认字段值] (https：//github.com/rust-lang/rfcs/pull/3681）
* [处理：合并] [特质方法实施限制](https://github.com/rust-lang/rfcs/pull/3678)

#### 跟踪问题和公关
#####  [Rust](https://github.com/rust-lang/rust/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc)
* [处理：合并] [添加针对函数指针比较的 lint](https://github.com/rust-lang/rust/pull/118833)
* [处理：合并] [实施 `From<&mut {slice}>` 1，用于 `Box/Rc/Arc<{slice}>`] (https：//github.com/rust-lang/rust/pull/129329）
* [处理：合并] [跟踪问题 `const_arguments_as_str`] (https：//github.com/rust-lang/rust/issues/103900）
* [处置：未指定] [将 lowerexp 和 upperexp 实现添加到非零](https://github.com/rust-lang/rust/pull/131377)
* [处理：合并] [稳定 `Ipv6Addr::is_unique_local` 并 `Ipv6Addr::is_unicast_link_local`] (https：//github.com/rust-lang/rust/pull/129238）
* [处理：合并] [ `std::os::darwin` 公开] (https：//github.com/rust-lang/rust/pull/123723）
* [处理：合并] [跟踪问题 `const_char_encode_utf16`] (https：//github.com/rust-lang/rust/issues/130660）
* [处理：合并] [浮动类型：将 copysign、ABS、signum 移动到 libcore](https://github.com/rust-lang/rust/pull/131304)
* [处理：合并] [跟踪问题 `{u8,i8,...}::isqrt`] (https：//github.com/rust-lang/rust/issues/116226）
* [处理：合并] [添加 `--print host-triple` 到打印主机目标三元组] (https：//github.com/rust-lang/rust/pull/125579）
* [处理：合并] [针对 `&T` 到 `&mut T` 和 `&T` 到 `&UnsafeCell<T>` 变形的线头] (https：//github.com/rust-lang/rust/pull/128351）
* [处理：合并] [Lint 反对从立即丢弃的临时对象中获取指针](https://github.com/rust-lang/rust/pull/128985)
* [处置：关闭] [考虑弃用 UB-happy `static mut`] (https：//github.com/rust-lang/rust/issues/53639）

#####  [Cargo](https://github.com/rust-lang/cargo/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc)

#####  [语言团队](https://github.com/rust-lang/lang-team/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc+)
*  *本周没有货物跟踪问题或 PRS 进入最后意见征询期。*

#####  [语言参考](https://github.com/rust-lang/reference/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc)
* [处置：未指明] [不同的“静态”项从不重叠](https://github.com/rust-lang/reference/pull/1657)

#####  [不安全代码指南](https://github.com/rust-lang/unsafe-code-guidelines/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc)
*  *本周没有不安全代码指南跟踪问题或 PRS 进入最终意见征询期。*

####  [新的和更新的 RFC](https://github.com/rust-lang/rfcs/pulls)
* [新增] [不安全的派生和属性](https://github.com/rust-lang/rfcs/pull/3715)
* [新增] [宏片段字段](https://github.com/rust-lang/rfcs/pull/3714)
* [新增] [宽松的 DST 字段排序](https://github.com/rust-lang/rfcs/pull/3713)

## 即将举办的活动

2024 - 10 - 23 - 2024 - 11 - 20 之间的生锈事件

### 虚拟的
* 2024 - 10 - 24| 虚拟 | [Rust中的女人](https://www.meetup.com/women-in-rust/)
    *  [** 第 4 部分（共 4 部分） - 黑客马拉松展示：最终项目和演示 **](https://www.meetup.com/women-in-rust/events/303213835/)
* 2024 - 10 - 24| 虚拟（德国柏林）| [柏林开放科技学校](https://berline.rs/)+ [Rust柏林](https://www.meetup.com/rust-berlin/)
    *  [** Rust黑客和学习 **](https://meet.jit.si/RustHackAndLearnBerlin)| [** 镜像：Rust黑客与学习聚会 **](https://www.meetup.com/rust-berlin/events/298633271/)
* 2024 - 10 - 25| 虚拟（美国新泽西州泽西城）| [泽西城优雅而好奇的编码员俱乐部合作社](https://www.meetup.com/jersey-city-classy-curious-coders-club-cooperative/)
    *  [** Rust编码/游戏开发星期五开放暴民会议！**](https://www.meetup.com/jersey-city-classy-curious-coders-club-cooperative/events/304100127/)
* 2024 - 10 - 26| 虚拟（格但斯克，PL) | [Stacja it Trójmiasto](https://www.meetup.com/stacja-it-trojmiasto/)
    *  [**Rust–Budowanie Narzïdzi Dziaïjïcych w Linii Komend**](https://www.meetup.com/stacja-it-trojmiasto/events/303550643/)
* 2024 - 10 - 29| 虚拟（美国德克萨斯州达拉斯）| [达拉斯Rust](https://www.meetup.com/dallasrust/)
    *  [** 上周二 **](https://www.meetup.com/dallasrust/events/301585671/)
* 2024 - 10 - 31| 虚拟（美国北卡罗来纳州夏洛茨维尔）| [夏洛茨维尔Rust聚会](https://www.meetup.com/charlottesville-rust-meetup/)
    *  [** 合作打造 Rust 中的口译员 **](https://www.meetup.com/charlottesville-rust-meetup/events/298898048/)
* 2024 - 10 - 31| 虚拟（德国纽伦堡）| [纽伦堡鲁斯特](https://www.meetup.com/rust-noris/)
    *  [** 纽伦堡Rust在线 **](https://www.meetup.com/rust-noris/events/300820274/)
* 2024 - 11 - 01| 虚拟（美国新泽西州泽西城）| [泽西城优雅而好奇的编码员俱乐部合作社](https://www.meetup.com/jersey-city-classy-curious-coders-club-cooperative/)
    *  [** Rust编码/游戏开发星期五开放暴民会议！**](https://www.meetup.com/jersey-city-classy-curious-coders-club-cooperative/events/gvxrntygcpbcb/)
* 2024 - 11 - 02| 虚拟（坎帕拉，乌干达）| [锈圈坎帕拉](https://www.eventbrite.com/o/rust-circle-kampala-65249289033/)
    *  [** Rust圈聚会 **](https://www.eventbrite.com/e/rust-circle-meetup-tickets-628763176587)
* 2024 - 11 - 06| 虚拟（印第安纳州印第安纳波利斯，美国）| [Indy Rust](https://www.meetup.com/indyrs/)
    *  [**Indy.rs-社交距离 **](https://www.meetup.com/indyrs/events/302031651/)
* 2024 - 11 - 07| 虚拟（德国柏林）| [柏林开放科技学校](https://berline.rs/)+ [Rust柏林](https://www.meetup.com/rust-berlin/)
    *  [** Rust黑客和学习 **](https://meet.jit.si/RustHackAndLearnBerlin)| [** 镜像：Rust黑客与学习聚会 **](https://www.meetup.com/rust-berlin/events/298633272/)
* 2024 - 11 - 08| 虚拟（美国新泽西州泽西城）| [泽西城优雅而好奇的编码员俱乐部合作社](https://www.meetup.com/jersey-city-classy-curious-coders-club-cooperative/)
    *  [** Rust编码/游戏开发星期五开放暴民会议！**](https://www.meetup.com/jersey-city-classy-curious-coders-club-cooperative/events/304099245/)
* 2024 - 11 - 12| 虚拟（美国德克萨斯州达拉斯）| [达拉斯Rust](https://www.meetup.com/dallasrust/)
    *  [** 第二个星期二 **](https://www.meetup.com/dallasrust/events/299346985/)
* 2024 - 11 - 14| 虚拟（美国北卡罗来纳州夏洛茨维尔）| [夏洛茨维尔Rust聚会](https://www.meetup.com/charlottesville-rust-meetup/)
    *  [** 合作打造 Rust 中的口译员 **](https://www.meetup.com/charlottesville-rust-meetup/events/298898070/)
* 2024 - 11 - 14| 虚拟和现场（美国华盛顿州西雅图）| [西雅图Rust用户组](https://www.meetup.com/seattle-rust-user-group/)
    *  [**11 月聚会 **](https://www.meetup.com/join-srug/events/304166747/)
* 2024 - 11 - 15| 虚拟（美国新泽西州泽西城）| [泽西城优雅而好奇的编码员俱乐部合作社](https://www.meetup.com/jersey-city-classy-curious-coders-club-cooperative/)
    *  [** Rust编码/游戏开发星期五开放暴民会议！**](https://www.meetup.com/jersey-city-classy-curious-coders-club-cooperative/events/gvxrntygcpbtb/)
* 2024 - 11 - 19| 虚拟（美国加利福尼亚州洛杉矶）| [DevTalk LA](https://www.meetup.com/lajugstudygroup/)
    *  [** 讨论 - 主题：Rust for UI**](https://www.meetup.com/lajugstudygroup/events/302952703/)
* 2024 - 11 - 19| 虚拟（华盛顿特区，美国）| [Rust DC](https://www.meetup.com/rustdc/)
    *  [** 月中生锈 **](https://www.meetup.com/rustdc/events/299346971/)
* 2024 - 11 - 20| 虚拟和现场（加拿大温哥华）| [温哥华锈病](https://www.meetup.com/vancouver-rust/)
    *  [** 预埋防锈车间 **](https://www.meetup.com/vancouver-rust/events/304047664/)

### 亚洲
* 2024 - 10 - 29| 日本东京 | [东京锈病会议](https://www.meetup.com/tokyo-rust-meetup/)
    *  [**Rust 中的无 bug 并发 **](https://www.meetup.com/tokyo-rust-meetup/events/304107583/)

### 欧洲
* 2024 - 10 - 26| 斯德哥尔摩，东南 | [斯德哥尔摩Rust](https://www.meetup.com/Stockholm-Rust/)
    *  [** 费里斯 FIKA 论坛 #6**](https://www.meetup.com/stockholm-rust/events/303918943/)
* 2024 - 10 - 28| 法国巴黎 | [Rust Paris](https://www.meetup.com/rust-paris/events/)
    *  [** Rust聚会 #71**](https://www.meetup.com/rust-paris/events/303663366/)
* 2024 - 10 - 29| 丹麦奥胡斯 | [鲁斯特 · 奥胡斯](https://www.meetup.com/rust-aarhus/)
    *  [** 黑客之夜 **](https://www.meetup.com/rust-aarhus/events/303479865)
* 2024 - 10 - 30| 德国汉堡 | [Rust聚会汉堡](https://www.meetup.com/rust-meetup-hamburg/)
    *  [**Rust Hack&amp;Learn 2024 年 10 月 **](https://www.meetup.com/rust-meetup-hamburg/events/303373054/)
* 2024 - 10 - 31| 德国柏林 | [柏林开放科技学校](https://berline.rs/)+ [Rust柏林](https://www.meetup.com/rust-berlin/)
    *  [**Rust and Tell-标题 **](https://www.meetup.com/rust-berlin/events/300820289/)
* 2024 - 11 - 06| 英国[牛津 Rust Meetup 集团](https://www.meetup.com/oxford-rust-meetup-group/)牛津
    *  [** 牛津Rust和 C++ 社交 **](https://www.meetup.com/oxford-rust-meetup-group/events/303123398/)
* 2024 - 11 - 06| 法国巴黎 | [巴黎Rust类](https://www.eventbrite.fr/o/paris-rustaceans-74289178383)
    *  [** 在巴黎举行的Rust聚会 **](https://www.eventbrite.fr/e/rust-meetup-in-paris-tickets-1037795553437)
* 2024 - 11 - 14| 斯德哥尔摩，东南 | [斯德哥尔摩Rust](https://www.meetup.com/Stockholm-Rust/)
    *  [**Rust Meetup@uxstream**](https://www.meetup.com/stockholm-rust/events/304124737/)
* 2024 - 11 - 19| 德国莱比锡 | [Rust-莱比锡的现代系统编程](https://www.meetup.com/rust-modern-systems-programming-in-leipzig/)
    *  [**Daten Sichern mit ZFS（与锈蚀）**](https://www.meetup.com/rust-modern-systems-programming-in-leipzig/events/302425200/)

### 北美洲
* 2024 - 10 - 23| 美国德克萨斯州奥斯汀 | [Rust ATX](https://www.meetup.com/rust-atx/)
    *  [** Rust午餐 - 机票 **](https://www.meetup.com/rust-atx/events/xvkdgtygcnbfc/)
* 2024 - 10 - 26| 美国新泽西州纽瓦克 | [NJ 代码 &amp; 咖啡](https://www.meetup.com/nj-code-coffee/)
    *  [** Rust简介：建立一个文本冒险游戏 X NJ 代码和咖啡 **](https://www.meetup.com/nj-code-coffee/events/304149949/)
* 2024 - 10 - 27| 美国马萨诸塞州坎布里奇 | [波士顿锈病会议](https://www.meetup.com/bostonrust/)
    *  [**Kendall Rust 午餐，10 月 27 日 **](https://www.meetup.com/bostonrust/events/303708359/)
* 2024 - 10 - 28| 美国科罗拉多州博尔德 | [博尔德Rust聚会](https://www.meetup.com/boulder-rust-meetup/)
    *  [** 从头开始的泛型 **](https://www.meetup.com/boulder-rust-meetup/events/303766925/)
* 2024 - 10 - 28| 美国密歇根州芬代尔 | [底特律Rust](https://www.meetup.com/detroitrust/)
    *  [**Rust 社区聚会-Ferndale**](https://www.meetup.com/detroitrust/events/303909299/)
* 2024 - 10 - 28| 美国明尼苏达州明尼阿波利斯市 | [明尼阿波利斯Rust聚会](https://www.meetup.com/minneapolis-rust-meetup/)
    *  [** 明尼阿波利斯Rust聚会欢乐时光 **](https://www.meetup.com/minneapolis-rust-meetup/events/303884468/)
* 2024 - 10 - 29| 美国田纳西州纳什维尔 | [音乐之城Rust开发商](https://www.meetup.com/music-city-rust-developers/)
    *  [** 乐城Rust开发商：集团现状及 2025 年预期 **](https://www.meetup.com/music-city-rust-developers/events/301425524/)
* 2024 - 10 - 30| 美国伊利诺伊州芝加哥 | [深盘锈](https://www.meetup.com/deep-dish-rust/)
    *  [**Rust Workshop：部署代码 **](https://www.meetup.com/deep-dish-rust/events/304071348/)
* 2024 - 11 - 04| 美国马萨诸塞州布鲁克莱恩 | [波士顿锈病会议](https://www.meetup.com/bostonrust/)
    *  [** 柯立芝街角布鲁克莱恩Rust午餐，11 月 4 日 **](https://www.meetup.com/bostonrust/events/303708387/)
* 2024 - 11 - 07| 美国密苏里州圣路易斯 | [STL Rust](https://www.meetup.com/stl-rust/)
    *  [** 使用 Rust 和 Bevy 引擎进行游戏开发 **](https://www.meetup.com/stl-rust/events/302371464/)
* 2024 - 11 - 12| 美国密歇根州安阿伯市 | [底特律Rust](https://www.meetup.com/detroitrust/)
    *  [** Rust社区聚会 - 安娜堡 **](https://www.meetup.com/detroitrust/events/cvdcntygcpbqb/)
* 2024 - 11 - 15| 墨西哥城，DF，MX| [Rust MX](https://www.meetup.com/rust-mx/)
    *  [** 多线程 Y Async En Rust Parte 2 - 智能尖头 Y 闭包 **](https://www.meetup.com/rust-mx/events/304150412/)
* 2024 - 11 - 15| 美国马萨诸塞州萨默维尔 | [波士顿锈病会议](https://www.meetup.com/bostonrust/)
    *  [**Ball Square Rust 午餐，11 月 15 日 **](https://www.meetup.com/bostonrust/events/303708398/)

### 大洋洲
* 2024 - 10 - 28| 澳大利亚维多利亚州墨尔本 | [Rust墨尔本](https://www.meetup.com/rust-melbourne/)
    *  [**2024 年 10 月 Rust 墨尔本会议 **](https://www.meetup.com/rust-melbourne/events/304034898/)
* 2024 - 10 - 29| 澳大利亚首都堪培拉 | [堪培拉Rust用户组（CRUG）](https://www.meetup.com/rust-canberra/)
    *  [** 六月聚会 **](https://www.meetup.com/rust-canberra/events/303128131/)
* 2024 - 10 - 31| 奥克兰，新西兰 | [Rust AKL](https://www.meetup.com/rust-akl/)
    *  [**Rust AKL：Rust on AWS：可持续发展 + 和平：零压力自动化 **](https://www.meetup.com/rust-akl/events/303824919/)

如果你正在运行 Rust 事件，请将其添加到 [日历] 中，以便在此处提及。也请记得添加活动链接。向 [Rust 社区团队] [社区] 发送电子邮件以获取访问权限。

[calendar]: https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com
[community]: mailto:community-team@rust-lang.org

## 工作
<!--

Rust Jobs:

TWiR has stopped featuring individual job postings. You can read more about this change here:

https://github.com/rust-lang/this-week-in-rust/issues/3412

-->

请看最新[谁在 R/Rust 上雇佣线程？](https://www.reddit.com/r/rust/comments/1fa0tf6/official_rrust_whos_hiring_thread_for_jobseekers/)的

# 本周语录

> 你的问题是你想向死人借钱。

– [/u/masklinn 在/R/rust 上](https://old.reddit.com/r/rust/comments/1g3a2ul/hey_rustaceans_got_a_question_ask_here_422024/lrzqed7/)

谢谢你[马切伊 · 齐亚尔德齐尔](https://users.rust-lang.org/t/twir-quote-of-the-week/328/1622)的建议！

 [请提交报价并为下周投票！](https://users.rust-lang.org/t/twir-quote-of-the-week/328)

*《Rust一周》由以下人员编辑：[内尔沙姆雷尔](https://github.com/nellshamrell)，[llogiq](https://github.com/llogiq)，[cdmistman](https://github.com/cdmistman)[埃里克塞帕宁](https://github.com/ericseppanen)[extrawurst](https://github.com/extrawurst)[安德鲁 · 波拉克](https://github.com/andrewpollack)[U007D](https://github.com/U007D)[kolharsam](https://github.com/kolharsam)[joelmarcey](https://github.com/joelmarcey)[玛丽安 · 戈尔丁](https://github.com/mariannegoldin)，，、，、，、[本尼瓦斯克斯](https://github.com/bennyvasquez)。*

* 电子邮件列表托管由 [Rust基金会](https://foundation.rust-lang.org/)* 赞助

<small> [关于 R/Rust 的讨论](REDDIT_LINK_HERE)</small>
