# 几何篇

## 微分流形

<details>

<summary><strong>Foundations of Differentiable Manifolds and Lie Groups(GTM 94) - Frank W. Warner</strong></summary>

推荐人(fffmatch)

这本书的入门知识只有微积分和线性代数，第六章需要熟练基本的傅里叶分析和实分析。

这或许算是一本几何的入门手册。此书的第1,2,4章很全面具体地展示了可微流形的基本性质和**张量计算**(这本书里面涉及的计算都是全局处理的，我很喜欢)，这三章关于可微流形的内容足够支撑几何初学者的后续学习(当然并不意味着读完这三章就完全掌握可微流形这个对象了，只是能保证你对基本的概念和语言有一个充分的认识)。

此书的第三章是李群的专题，也是一个值得推荐的入门级材料。至少我关于李群的知识只有这一章，但也能做到在别的教材牵涉到李群的时候勉勉强强够用。

第五章讲的是从层的上同调切入构建德拉姆上同调，奇异上同调与Cech上同调(其实还有个Alexander - Spanier上同调但我涉及很浅不知道这东西有啥用)。阅读此章理论上不需要前置知识，但如果熟悉同调代数的话读起来会轻松愉快(因为很大一部分的内容就在构建导出函子)。

另外第五章的主定理就是德拉姆定理。如果目的只是学习德拉姆定理的话其实还有另一个用MV序列的选项(参见下面推荐的**Differential Forms in Algebraic Topology(GTM 82) - Bott & Tu**)，就不很需要同调代数了。

第六章讲的是基本的Hodge理论，也是自洽的内容(前提是知道基本的通用分析学：实分析复分析傅里叶分析)。从中你能学到基本的椭圆方程(系统)理论，**十分推荐此章，作为入门材料甚至比专门的方程教材要让人容易接受。**



</details>

### 古典微分几何(黎曼几何)

<details>

<summary><strong>Riemannian Geometry - Do Carmo</strong></summary>

推荐人(fffmatch)

这本书的入门知识理论上只有微积分与线性代数，但如果熟悉一些基本的微分流形就更好。

整本书非常的稳扎稳打，中规中矩，首先学习什么是度量，联络，曲率，测地线，雅克比场。然后展现了曲率对流形拓扑产生影响的经典结果：单连通常曲率空间的分类，严格正Ricci曲率空间的紧性，定向与单连通性（Cartan，Bonnet-Myers与Synge)等等。 另一方面，这本书也介绍了基本的Morse理论(但不全面)，并且给出了1/4 pinch定理的证明(我很喜欢这个定理，非常漂亮)。

但只读Do Carmo这本书是很有局限性的。 其实我觉得引入曲率和雅克比场有不少更自然的方法。一方面，曲率可以从和乐的角度理解，粗浅来说就是向量场沿着曲线平行移动一周并不一定移动到自身，这就是曲率带来的影响(这方面内容可以在熟悉了曲率后阅读**Petersen的Riemannian geometry**相关章节)。另一方面，曲率也可以看成曲线能量求二阶微分的产物。实际上，围绕着曲线能量的变分就可以发展Morse Theory，见下面的推荐。很建议如果有代数拓扑基础，读完Do carmo后阅读**Morse theory-Milnor**，由于内容有不少重合性，很快就能读完。

Do Carmo本身的体量也不是很丰富，后续可以选读**Comparison theorems in Riemann geometry-Cheeger(主要是上面有一些好用的比较定理)以及Riemannian geometry-Petersen**，以及更多相关教材进行补充(在此再提名一下伍鸿熙先生的**黎曼几何初步**，也是很好的书。)

</details>

<details>

<summary><strong>Morse Theory - Milnor</strong></summary>

(推荐人:fffmatch)

阅读此书需要基本的代数拓扑知识(第一章需要知道什么是CW复形以及同伦群的非常基础的性质，第四章需要知道纤维丛的基本知识，下面推荐的**Differential Forms in Algebraic Topology(GTM 82) - Bott & Tu**中关于同伦论的复习基本就够用)。

Milnor写的书都非常精彩，而这一本算是精彩中的精彩。书中第一章介绍了Morse理论的基本内容：流形沿着其上的函数的梯度流可以同伦等价地形变，在经过(非退化的)奇异点时流形的拓扑会发生变化(会粘上去一个胞腔)，胞腔的维数等价于二阶微分的指标，因此流形上合适的函数可以解释流形的拓扑性质。

第二第三章从道路能量的变分开始，将Morse理论“推广”到了黎曼流形的道路空间上(这个推广并不是直接在道路空间上做，而是把道路空间用一致有限能量的分段测地线穷举)，其作为黎曼几何的入门材料也是非常适合的。之所以做这个推广，是因为道路空间的n维同伦信息就是原来空间的n+1维同伦信息。另一方面，在测地线上，能量的二阶微分(也就是我们函数的指标)，与曲率和雅克比场的发展息息相关，**因此我们可以把流形的曲率信息传到道路空间的同伦信息，再回传到流形的同伦信息。**

第四章将研究对象放到了李群上，并且向着主定理：Bott Periodicity发起了进攻。复的Bott Periodicity的证明和结论都很简洁优雅，而实的证明我并没有看下来，但结论依旧是非常striking的。

似乎看完这本书还推荐看Milnor的h-cobordism讲义，不过我还没看()。

</details>

## 拓扑

<details>

<summary><strong>基础拓扑学-尤承业</strong></summary>

(推荐人:fffmatch)

如果你看过卓里奇，可以花一点点时间看这本书基本群以及其以前的部分来补充一些点集拓扑的知识，后面代数拓扑的部分就不必阅读了，有更好的教材。

</details>

<details>

<summary><strong>Topology from the Differentiable Viewpoint - Milnor</strong></summary>

(推荐人:fffmatch)

算是一本适合大一学生阅读的拓扑书籍，Milnor最亲民的教材，阅读它只要熟练多元微积分即可！这本书中你可以轻松地证明布伦威尔不动点定理，可以初探映射度来取得一些奇妙的拓扑结果(比如所谓“无毛定理”)，可以挖掘出向量场和欧拉示性数的关系(Hopf Index定理)，甚至最后一章可以教会你一个事实上不甚平凡的拓扑结果：计算$n$维球面的第$n$个同伦群(Pontryagin Framed Cobordism)。对于初学者，这本书是认识拓扑学，激发拓扑学兴趣的极好材料。

</details>

<details>

<summary><strong>Algebraic Topology - Hatcher</strong></summary>

(推荐人:fffmatch)

个人认为代数拓扑是一个很难入门的学科，不同的人往往会推荐不同的教材。

Hatcher的书是被最多人推荐的书籍，他的优点在于重视几何直观，不会让入门者迷失在抽象的代数构造中，并且整个书籍的叙述非常细致，选材也足够充分：除了基本的基本群，同调群，上同调环，同伦群与纤维化以外，他有很多进阶的补充专题，每个专题都是非常经典重要的结果(不过我自己其实这本书也没有看完，还在学习中)。

但Hatcher的书缺点也在于他有时候实在是太啰嗦了，容易让行文太冗长，不过这是一些耐心就能克服的事情，我个人认为不能因此否决掉Hatcher的书的优点。总之这应该是能满足侧重几何的学习者需求的书籍。最后Hatcher里面也包含了需要使用的同调代数内容，写的很不错容易理解，不过还是建议另外找本同调代数的书对照阅读。

</details>

<details>

<summary><strong>Differential Forms in Algebraic Topology(GTM 82) - Bott &#x26; Tu</strong></summary>

（推荐人:fffmatch）

这是一本广受好评的书籍，就像书名所说，这本书用微分形式漂亮地解释了很多代数拓扑里的结果，比如子流形的庞加莱对偶对应着子流形法丛的Thom类(可以说是子流形的”特征微分形式“)，用此我们可以定义横截子流形的相交。与此同时，这本书的第二第三章还是一个非常好的入门谱序列的材料(谱序列本身是一个困难的同调代数工具)，最直接的应用就是说明了切赫上同调和德拉姆上同调是一致的，这也揭示了流形的拓扑学很大程度上取决于他里面单连通开集粘合的组合学。

第三章里还包含了一小块同伦论的内容，是一个快速了解纤维丛的不错专题。

最后一章的主要内容是示性类，拓展了这本书前面提到的欧拉类，建议和Milnor的**Characteristic Classes**一起阅读(不过Milnor这本书还是需要找一些别的材料补充，为了绕过里面用到的Steenrod algebra，一个参考是石溪大学的微分拓扑的讲义)。Milnor的书使用classifying space定义了一般的示性类，非常的漂亮，而Bott的这本书则解释了更加具体的构造(将向量丛投影化后之后split降维)，两本书一起读的效果会很好。

</details>

<details>

<summary><strong>An Introduction to Algebraic Topology(GTM 119) - Joseph J. Rotman</strong></summary>

(不推荐人:fffmatch)

这是一本**很不推荐作为入门教材的代数拓扑书籍**，主要是叙述实在是过于事无巨细，不突出重点。并且其对同伦群和上同调的叙述篇幅太少了，每个只有一章。

</details>

## 黎曼曲面

<details>

<summary><strong>Lectures on Riemann Surfaces(GTM81) - Otto Forster</strong></summary>

（推荐人:fffmatch）

经典的黎曼曲面教材，包含了绝大部分的常用内容，包括复叠空间(作为基本的预备知识)，Riemann Hurwitz公式与Riemann Roch定理(用Serre Duality证明)，Abel定理和Jacobi Inversion，单值化定理(证明方式是Runge exhaustion加解拉普拉斯方程，其实用拉普拉斯方程证明区域上的黎曼映照定理这个想法好像就来自黎曼本人，值得学习)，线丛以及一些别的章节。这本书对这些内容的处理或许可以称的上是“标准”的，没有走向过于抽象或者过于分析技术的风格，前置知识的要求需要一些对流形和拓扑的熟悉程度(如果没有操作过上同调的话可能第二部分会读不下去)，总体很值得学习。

</details>

<details>

<summary><strong>Compact Riemann surfaces - Jürgen Jost</strong></summary>

(推荐人:fffmatch)

一本神奇的小书，第一第二第五章算是软的几何，分类了紧的双曲曲面以及讨论了一些双曲度量的性质，证明了Riemann Hurwitz公式，Riemann Roch定理，Abel定理和Jacobi Inversion等等经典结果(不过有些处理就非常的“古典”，比如黎曼罗赫定理的处理巨大使用了线性代数...)。不过这也导致学这部分内容需要的前置知识更少(大概只需要一些基础的拓扑和微分几何)，有兴趣可以尝试阅读。

第三第四章是硬的几何，用调和映射讨论了Teichmuller理论，我没读下来，感觉是过于神奇的处理方式。

</details>

<details>

<summary><strong>An Introduction to Teichmüller Spaces - Imayoshi</strong></summary>

(推荐人:fffmatch)

我学习Teichmüller理论的入门书，质量尚可，内容编排很合理，不过对内容的处理或许有一些小瑕疵：第一是有些地方叙述过于啰嗦不突出重点，第二是有些证明会跳步需要另外查阅或者自己补gap，然后对于一些内容的处理方式也不是最佳的，比如Schwarzian比如Weill Petersen Metric的Kahlerity(这些内容可以用下面推荐的Hubbard的书弥补)。总体而言可以作为入门书籍阅读。

</details>

<details>

<summary><strong>Teichmüller Theory and Applications to Geometry, Topology and Dynamics-Volume 1, John H. Hubbard</strong></summary>

(推荐人:fffmatch)

这是一套书，出到了第四本。第一本主要关于Teichmuller理论，第二本关于复动力系统，第三第四本关于三维流形。目前我只能获得第一本orz。

此书是非常好的一本书，主要推荐理由是他对一些内容的处理方式是非常nice的，比如上述的Schwarzian，Imayoshi的书没有解释清楚这个量的动机，但是Hubbard用射影结构解释了，以及Imayoshi对Weill Petersen Metric的Kahlerity的证明是局部的(也就是狠狠地展开成张量计算)，而Hubbard这本书里的处理是全局的(概括而言用Simultaneous Uniformization与射影结构的变化计算出了Kahler Form的potential，所以实际上Kahlerity是更强的)。

其次是这本书写的非常生动，图很多，对概念的动机解释和历史发展也很多，我很喜欢这种风格的作者。

最后这本书的编排也很不错，内容非常丰富(其实他是从黎曼面的单值化写起的，如果没接触过黎曼曲面的话，或许也可以从这本书从零开始学？)

</details>

<details>

<summary><strong>The Geometry of Discrete Groups - Alan F. Beardon</strong></summary>

(推荐人:fffmatch)

归类不一定合适。这本书的主角为Fuchsian Group与Kleinian Group，是研究曲面，复动力系统，二，三维拓扑和几何群论的核心对象。不过我读这本书的主要感受是难以及有些无聊(所以也没读完)，难是因为他的处理方式很注重于技术，无聊是因为他把Fuchsian Group与Kleinian Group作为了孤立的对象叙述，很多定理应该是有别的分支的背景的，但他都没有解释。不过好处是这本书收纳了非常多且强的关于这些群的性质和工具，可以作为参考书查阅。

</details>
