# 安全資産に関する2論文まとめ

---

## 論文① Damodaran (2008)
### "What is the riskfree rate? A Search for the Basic Building Block"

---

### 1. リスクフリー資産の定義

#### 日本語まとめ

リスクフリー資産とは「実際のリターンが常に期待リターンと等しい投資」である。
ファイナンスにおけるリスクは期待リターンを中心とした実際リターンの分散として捉えられるため、
リスクフリーな投資においては実際のリターンは常に期待リターンと等しくなければならない。
また、リスクフリー資産は他のリスク資産のリターンと無相関であるべきとされる。

#### 原文

> "Risk in finance is viewed in terms of the variance in actual returns around the expected return.
> For an investment to be risk free in this environment, then, the actual returns should always be
> equal to the expected return."

> "There is a second way in which we can think of a riskfree investment and it is in the context
> of how the investment behaves, relative to other investments. A riskfree investment should have
> returns that are uncorrelated with risky investments in a market. Note that if we accept the
> first definition of a riskfree asset as an investment with a guaranteed return, this property
> always follows. An investment that delivers the same return, no matter what the scenario, should
> be uncorrelated with risky investments with returns that vary across scenarios."

---

### 2. リスクフリー資産の2つの必要条件

#### 日本語まとめ（第一条件：デフォルトリスクなし）

リスクフリー資産の第一条件は、デフォルトリスクが存在しないことである。
これは民間企業が発行するいかなる証券も除外する。政府証券のみがリスクフリーになりうるが、
それは政府が通貨の印刷を管理しており、少なくとも名目ベースでは約束を履行できるからである。

#### 原文（第一条件）

> "The first is that there can be no default risk. Essentially, this rules out any security issued
> by a private firm, since even the largest and safest firms have some measure of default risk.
> The only securities that have a chance of being risk free are government securities, not because
> governments are better run than corporations, but because they control the printing of currency.
> At least in nominal terms, they should be able to fulfill their promises."

#### 日本語まとめ（第二条件：再投資リスクなし）

第二条件は再投資リスクが存在しないことである。
例えば6ヶ月物の財務省短期証券はデフォルトフリーではあるが、6ヶ月後の金利が不明なため
再投資リスクがあり、リスクフリーとは言えない。
5年間の時間軸に対するリスクフリーレートは、デフォルトフリーの5年ゼロクーポン債の
期待リターンでなければならない。

#### 原文（第二条件）

> "There is a second condition that riskless securities need to fulfill that is often forgotten.
> For an investment to have an actual return equal to its expected return, there can be no
> reinvestment risk. To illustrate this point, assume that you are trying to estimate the expected
> return over a five-year period, and that you want a risk free rate. A six-month treasury bill
> rate, while default free, will not be risk free, because there is the reinvestment risk of not
> knowing what the treasury bill rate will be in six months. Even a 5-year treasury bond is not
> risk free, since the coupons on the bond will be reinvested at rates that cannot be predicted
> today. The risk free rate for a five-year time horizon has to be the expected return on a
> default-free (government) five-year zero coupon bond."

---

### 3. リスクフリーレートはなぜ重要か

#### 日本語まとめ

リスクフリーレートは株式コストと資本コストの両方を推定するための基礎である。
株式コストはリスクフリーレートにリスクプレミアムを加えることで計算され、
負債コストはリスクフリーレートにデフォルトスプレッドを加えることで推定される。
リスクフリーレートが高くなると割引率が上昇し、DCF評価において現在価値が減少する。
また、リスクフリーレートの上昇は成長企業に対してより大きな悪影響を与える。

#### 原文

> "The riskfree rate is the building block for estimating both the cost of equity and capital.
> The cost of equity is computed by adding a risk premium to the riskfree rate, with the magnitude
> of the premium being determined by the risk in an investment and the overall equity risk premium
> (for investing in the average risk investment). The cost of debt is estimated by adding a default
> spread to the riskfree rate, with the magnitude of the spread depending upon the credit risk in
> the company. Thus, using a higher riskfree rate, holding all else constant, will increase
> discount rates and reduce present value in a discounted cash flow valuation."

> "Since growth assets deliver cash flows way into the future, the effect of the riskfree rate is
> much greater. [...] If we categorize companies, based upon assets in place and growth assets,
> growth companies should be affected much more adversely when the riskfree rate increases than
> mature companies, holding all else constant."

---

### 4. 実務上の推奨：10年国債の利用

#### 日本語まとめ

実務上、企業価値評価のキャッシュフローのデュレーションは長期に及ぶため、
デュレーションマッチングの観点から10年国債レートをリスクフリーレートとして
使用することが妥当である。S&PはS&P500の株式デュレーションを約16年と推定しており、
配当よりキャッシュフローベースでは8〜9年程度となる。
10年クーポン債のデュレーションは約8年に近いため、ほとんどの成熟企業において
10年国債レートが適切なリスクフリーレートとなる。

#### 原文

> "In most business valuations, we can safely assume that the duration of the cash flows will be
> high, especially if we assume that cash flows continue into perpetuity. S&P used the dividend
> discount model to estimate the duration of equity in the S&P 500 to be about 16 years in 2004.
> Since dividends are lower than cashflows to equity, we would expect the true duration to be
> lower and closer to 8 or 9 years for the S&P 500. Since the duration of a 10-year coupon bond
> (with a coupon rate of about 4%), priced at par, is close to 8 years, this would lead to use
> the 10-year treasury bond rate as the riskfree rate on all cash flows for most mature firms."

> "Given that the difference between the 10-year and 30-year bond rates is small and that it is
> much easier estimating equity risk premiums and default spreads against the former rather than
> the latter, we believe that using the 10-year bond rate as the riskfree rate on all cash flows
> is a good practice in valuation, at least in mature markets."

---

### 5. 通貨によるリスクフリーレートの差異

#### 日本語まとめ

リスクフリーレートが通貨によって異なる主因は期待インフレ率の差異である。
高インフレ通貨は低インフレ通貨よりも高いリスクフリーレートをもつ。
評価に使用するリスクフリーレートは、キャッシュフローと同一通貨で測定されるべきであり、
企業の所在国ではなくキャッシュフローの通貨によって決定される。

#### 原文

> "Since the rates that we have specified as riskfree rates are all over the same maturity (ten
> years) and are default-free, the only significant factor that can cause differences is expected
> inflation. High inflation currencies will have higher riskfree rates than low inflation
> currencies."

> "Summarizing, the risk free rate used to come up with expected returns should be measured
> consistently with the cash flows are measured. Thus, if cash flows are estimated in nominal US
> dollar terms, the risk free rate will be the US Treasury bond rate. This will remain the case,
> whether the company being analyzed is a Brazilian, Indian or Russian company."

---

### 6. 政府がデフォルトリスクを持つ場合

#### 日本語まとめ

新興国では政府債にもデフォルトリスクが含まれる場合がある。
その場合、市場金利からデフォルトスプレッドを差し引くことで
真のリスクフリーレートを推定することができる。
例えばインドの場合、ルピー建て国債の市場金利10.7%からデフォルトスプレッド2.6%を
差し引くことでリスクフリーレート8.10%が得られる。

#### 原文

> "Since the problem in this case is that the local currency bond rate includes a default spread,
> the solution is a fairly simple one. If we can estimate how much of the current market interest
> rate on the bond can be attributed to default risk, we can strip this default spread from the
> rate to arrive at an estimate of the riskfree rate in that currency. Using the Indian rupee bond
> again as the illustration, we used the local currency rating for India as the measure of default
> risk to arrive at a default spread of 2.6%. Subtracting this from the market interest rate
> yields a riskfree rupee rate of 8.10%."

---

### 7. 実務上の3つのルール

#### 日本語まとめ（ルール1）

リスクフリーレートは真にリスクがないものでなければならない。
デフォルトやその他の要因に対するリスクスプレッドが含まれているレートはリスクフリーレートではない。
多くの新興国の現地通貨建て政府国債レートはリスクフリーレートとして使用できない。

#### 原文（ルール1）

> "Rule 1: A riskfree rate should be truly free of risk. A rate that has risk spreads embedded
> in it for default or other factors, is not a riskfree rate. This is why we argued that local
> currency government bond rates in many emerging markets cannot be used as riskfree rates."

#### 日本語まとめ（ルール2）

キャッシュフローの定義と一致したリスクフリーレートを選択すること。
キャッシュフローが実質ベースであればリスクフリーレートも実質ベース、
特定通貨であればその通貨のリスクフリーレートを使用する。

#### 原文（ルール2）

> "Rule 2: Choose a riskfree rate that is consistent with how cash flows are defined. Thus, if
> the cash flows are real, the riskfree rate should also be real. If the cash flows are in a
> specific currency, the riskfree rate has to be defined in that currency."

#### 日本語まとめ（ルール3）

金利について強い見解を持っていても、それを個別企業の評価に持ち込まないこと。
リスクフリーレートに対する見解を評価に反映させると、金利観と企業評価が混在し、
各効果を解読することが困難になる。

#### 原文（ルール3）

> "Rule 3: If you have strong views on interest rates, try to keep them out of the valuation of
> individual companies. In other words, even if you believe that riskfree rates will rise or fall
> over time, it is dangerous to reflect those views in your valuation."

---

---

## 論文② Golec & Perotti (2017, ECB Working Paper No. 2035)
### "Safe assets: a review"

---

### 1. 安全資産の定義

#### 日本語まとめ（基本定義）

安全資産とは「信用リスクのない無条件の金融的約束、すなわち名目上の返済が確実なもの」である。
これは「安全な」政府（独自の中央銀行・安定した通貨・財産権の良好な保護を持つ国）
によって発行または保証された債務を安全と定義する。
なお、絶対的に安全な資産は存在しないという前提のもとでこの定義が使用される。

#### 原文（基本定義）

> "Naturally, no asset is absolutely safe. We will use the term safe assets to describe
> unconditional financial promises with no credit risk, so that nominal repayment is certain.
> This defines as safe any debt issued or guaranteed by a 'safe' government, implying a country
> with an own central bank, stable currency and good protection of property rights."

#### 日本語まとめ（準安全資産）

最も安全な民間発行クレームを「準安全（quasi-safe）」と定義する。
これは大規模な危機以外ではクレジットリスクがないことを意味する。
ほとんどの民間準安全資産は短期・有担保債務などの民間仲介機関によるインサイドマネー創造の
過程で生まれる。通常は安全であるが、システミックな混乱の際には安全性の認識を失い
急速に非流動的となる。

#### 原文（準安全資産）

> "We define the safest privately issued claims as quasi-safe, implying that they have no credit
> risk outside of major crises. Most private quasi-safe assets arise in the process of inside
> money creation by private intermediaries, such as short term and secured debt. While generally
> safe, at time of systemic distress, these private assets lose their perceived safety and become
> rapidly illiquid."

---

### 2. 安全性・流動性・マネー需要の区別

#### 日本語まとめ（マネー需要）

伝統的なマネー需要は、現金・準備金・要求払い銀行債務など即時の支払い手段として機能する
クレームを求める。これは金利リスクもゼロの究極の流動的かつ名目安全資産であるが、
即時決済手段としてのコンビニエンスイールドも享受するため、純粋な安全性目的では
他の安全資産に劣る。

#### 原文（マネー需要）

> "Traditional money demand seeks claims that serve as immediate form of payment, such as cash,
> reserves or demandable bank debt. It is the ultimate liquid and nominally safe asset, which also
> has zero interest-rate risk. While it can serve as a low return store of value, for purely
> safety purposes it is dominated by other safe assets, since it also enjoys a convenience yield
> due to its immediate use as payment."

#### 日本語まとめ（流動性需要）

流動性需要は、政府債務や流動性へのアクセスがある借り手が発行する短期債務など、
素早く現金に換金できる資産を求める。消費や投資のための突然の需要を満たすことができる
という点で価値がある。

#### 原文（流動性需要）

> "Liquidity demand seeks assets easily converted into money quickly, such as government debt and
> short term debt issued by borrowers with access to liquidity. Asset liquidity is valued as it
> can satisfy sudden needs for consumption or investment, either for consumption or productive
> purposes."

#### 日本語まとめ（安全性需要）

安全性需要は支払い手段へのアクセスを求めるのではなく、あらゆる状態での資産保全を目指すもので、
極端なリスク回避行動をもたらす。したがって公的債務や最も安全な民間資産を対象とする。

#### 原文（安全性需要）

> "safety demand does not seek access to means of payment, but is aimed at wealth preservation
> in all states, resulting in extreme risk avoiding behavior. It therefore targets public debt or
> the safest private assets."

#### 日本語まとめ（安全性と流動性の区別）

安全性と流動性の区別は概念的には明確だが、長らく無視されてきた。
安全資産は通常は非常に流動的であるが、一部の安全資産は構造上非流動的（例：保険付き定期預金、
ターム・レポ）であり、逆に上場株式などの非常にリスクの高い資産が危機時に社債やABSより
流動的であることもある。

#### 原文（安全性と流動性の区別）

> "The distinction between safety and liquidity is conceptually sharp but has long been neglected,
> for good reasons. First, safe assets are typically very liquid, provided they have an active
> secondary market. However, empirically the distinction is possible. Some safe assets are
> illiquid by construction (e.g. insured savings deposits, or term repo on safe collateral).
> In contrast, some very risky assets such as listed shares can be more liquid during a crisis
> than much safer assets such as corporate bonds or rated ABS."

---

### 3. 安全資産への需要の根拠

#### 日本語まとめ（①ナイト的不確実性アプローチ）

絶対的安全性への分断された需要を導入するには、古典的な効用最大化フレームワークに
ある種の不連続性が必要である。一部の極端な状況では、エージェントはもはや資産の
リスク・リターンのトレードオフを評価できなくなる（ナイト的不確実性）。
その結果、無限の危険回避を持つかのように最悪シナリオのみを考慮するようになる。

#### 原文（①ナイト的不確実性）

> "The introduction of a segmented demand for absolute safety requires some discontinuity in the
> classic utility maximization framework. For example, infinite risk aversion arise episodically
> in response to shocks to beliefs. In some extreme contingencies, agents may no longer be able
> to assess the risk return tradeoff of assets or the allocation of losses across counterparties,
> a form of Knightian uncertainty (Caballero and Krishnamurthy, 2008). As a result they only
> consider worst-case scenarios, as if they had infinite risk aversion."

#### 日本語まとめ（②Stone-Geary型効用関数アプローチ）

Ahnert and Perotti (2015) はStone-Geary効用関数を用いて構造的な安全性需要を直接モデル化する。
この選好の下では、個人は巨大な効用損失を避けるためにあらゆる状態で最低限の生存レベルの富を
達成する必要がある。したがって、残余ポートフォリオでリスクを取る前に安全な価値の保存手段を
確保しなければならない。

#### 原文（②Stone-Geary型効用関数）

> "A different framing presumes that all investors have a structural demand for safety in the
> context of their portfolio choice. Ahnert and Perotti (2015) model directly a structural safety
> demand by assuming a version of the Stone-Geary utility function, which is often used in the
> context of development economics. Under such preferences, individuals need to attain a minimum
> subsistence (survival) level of wealth in all states to avoid a huge loss in utility. Thus a
> safe storage of value needs to be secured before agents absorb any risk in their residual
> portfolio."

#### 日本語まとめ（③流動性需要から生じる安全需要）

内生的逆選択に基づく近年のモデルでは、安全資産への需要は流動性需要からも生じ得る。
ファンダメンタルリスクが低い場合、情報取得インセンティブがないため資産は非流動性から
「安全」である。しかし悪いニュースが届きリスクが閾値を超えると、全ての準安全クレームが
非流動的になる可能性があり、急激なデレバレッジが強制される。

#### 原文（③流動性需要から生じる安全需要）

> "In recent models based on endogenous adverse selection, a demand for safe assets may also
> originate from a demand for liquidity (Dang et al. (2012), Farhi and Tirole, 2014). When
> fundamental risk is low an asset is 'safe' from illiquidity because there are little incentives
> to acquire information about it. However, relying on common ignorance for liquidity provision
> in good times may create occasional sharp crises. When bad news arrives and fundamental risk
> passes a threshold, investors have incentives to learn about risk, so in principle all quasi
> safe claims may become illiquid. This forces sharp deleveraging, in order to restore an
> information-insensitive payoff structure."

---

### 4. 安全プレミアムの実証証拠

#### 日本語まとめ（基本的な証拠）

Krishnamurthy and Vissing-Jorgensen (2012) は1926〜2008年のデータを用いて、
デフォルトリスクをコントロールした社債と国債の利回りスプレッドが民間保有政府債務の
GDP比と強く負の相関することを示した。国債の供給が少ない時ほど投資家はより高いプレミアムを
支払おうとし、その影響は大きく（Baa格付け社債と国債のスプレッドの73bpが国債供給で説明）、
安全資産の価格が需要・供給ショックに敏感であることを示す。

#### 原文（基本的な証拠）

> "Krishnamurthy and Vissing-Jorgensen (2012) provide historical evidence of a strong price
> sensitivity of safe assets to demand and supply shocks. The yield spread between corporate and
> Treasury bonds, controlling for default risk, is strongly negatively correlated with the ratio
> of privately held government debt to GDP from 1926 to 2008. Whenever the supply of public debt
> is low, investors are willing to pay a higher premium for Treasuries. The magnitude of the
> effect is large, with an average spread of 73bp between Baa-rated corporate bonds and
> Treasuries explained by Treasury supply."

#### 日本語まとめ（安全プレミアムと流動性プレミアムの分解）

国債プレミアムは流動性プレミアム（最大46bp）と安全性プレミアム（少なくとも27bp）に
分解できる。流動性プレミアムの特定には、同等に安全だが満期まで非流動的なCDと
財務省短期証券のスプレッドを用いる。安全性プレミアムには同一満期で同等に非流動的な
商業ペーパーのスプレッドを用いる。

#### 原文（プレミアムの分解）

> "This insight allows to decompose the premium on Treasuries into a liquidity (at most 46 bp)
> and safety premium (at least 27 bp). To identify the liquidity premium, they regress public
> debt on the yield spread between 6 months insured certificates of deposits (CDs) and Treasury
> Bills, finding a negative relationship. This spread captures the liquidity premium, as both
> assets are equally safe but CDs are illiquid until maturity."

---

### 5. 民間による安全資産の創出とシステミックリスク

#### 日本語まとめ（創出のメカニズム）

安全プレミアムを狙って、仲介機関はより安全なクレームを切り出すか安全な資産を担保提供する
ことで安全性を約束できる。信用ブーム期には証券化によりリスクを共有し、
リスク回避投資家向けの安全なABSトランシェを創出した。
しかしこの不動産ローン証券化は信用リスクを再分配した一方で、収益の相関を大幅に高め、
リスクが顕在化した際のシステミックな連鎖を強化した。

#### 原文（創出のメカニズム）

> "To take advantage of the safety premium, intermediaries can promise safety by carving out
> safer claims and/or pledging safer assets. Diversification is the classic solution to reduce
> the risk of assets against which investors lend. In response to strong safety demand during the
> credit boom, intermediaries shared risks via loan securitization, and created safer ABS tranches
> that may be pledged or placed in special investment vehicles that may be funded by risk avoiding
> investors. Diversification via real estate loan securitization had the effect to redistribute
> credit risk across intermediaries, but as a consequence it led to a major increase in their
> return correlation."

#### 日本語まとめ（安全クレーム発行の条件）

仲介機関が安全クレームを発行するためには、まず財産権の信頼できる執行が必要である。
名目上の安全資産は無条件の約束（債務クレーム）である必要があり、
担保化・満期・優先順位などの契約条件によって安全性をさらに強化できる。

#### 原文（発行の条件）

> "The ability of intermediaries to issue safe claims requires first and foremost a reliable
> enforcement of property rights. Thus only intermediaries in countries with a solid political
> and fiscal position may become eligible as issuers of safe assets. Next, a nominal safe asset
> needs to be an unconditional promise, thus a debt claim. But debt safety may be further
> strengthened by contractual terms, such as collateralization (secured debt), maturity (time
> priority) and seniority (contractual priority at default)."

---

### 6. 「安全性の罠（Safety Trap）」とマクロ経済への含意

#### 日本語まとめ

Caballero and Farhi (2015) は、安全資産の急激な減少が「安全性の罠」をもたらしうると主張する。
安全資産市場は通常、供給減少時に安全金利の低下によって清算されるが、
ゼロ下限ではこれが不可能であるため、唯一可能な調整は深刻なリセッションを通じた
安全資産への需要削減となる。
ケインズ的な流動性の罠とは異なり、安全性の罠は安全資産の不足を表しており、
リスク資産の価値を高めるフォワードガイダンスのような政策は無効となる。

#### 原文

> "Caballero and Farhi (2015) argue that a sharp decline in (quasi-)safe assets can lead to a
> situation called the safety trap. While the market for safe assets usually clears via a
> reduction in the safe rate when there is a drop in supply, this is not possible at the zero
> lower bound. The only possible adjustment is through a deep recession that reduces demand for
> safe assets via a wealth effect. In contrast to the Keynesian liquidity trap, where there is
> a shortage of assets in general, the safety trap represents a shortage of safe assets.
> Therefore, policies such as forward guidance that increase the value of risky assets are futile
> in the safety trap."

---

---

## 2論文の主な見解の比較

| 観点 | Damodaran (2008) | Golec & Perotti (2017) |
|------|-----------------|----------------------|
| **定義の焦点** | 個別評価・企業金融における実務的なリスクフリーレートの推定 | マクロ・金融システム全体における安全資産の需要と供給 |
| **安全性の条件** | デフォルトリスクなし＋再投資リスクなし | 名目返済の確実性＋信用リスクなし（危機時を除く） |
| **主な安全資産** | 政府発行のゼロクーポン国債（実務上は10年国債） | 政府債務＋民間の準安全資産（短期・有担保債務） |
| **流動性との関係** | 主に言及なし | 安全性と流動性を概念的に明確に区別 |
| **民間の役割** | 民間はデフォルトリスクがあるためリスクフリーになりえない | 民間は安全プレミアムを狙い「準安全資産」を創出（但し危機時に脆弱） |
| **政策含意** | 評価上の一貫性（通貨・期間の整合性） | マクロプルーデンシャル規制・政府債務管理 |

> **総括：**
> 両論文は「安全資産＝政府発行の債務が中核」という点では一致しつつも、
> Damodaranが**実務的な評価の枠組み**を重視するのに対し、
> Golec & Perottiは**安全資産への需要が金融システムや信用サイクル全体に与える影響**まで
> 射程を広げている点が大きな違いである。
