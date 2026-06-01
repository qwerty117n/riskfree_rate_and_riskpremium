# リスクプレミアムに関する主要学術論文：主張と原文

> 各論文におけるリスクプレミアムの定義・主張を、核心的な原文フレーズとともにまとめたものです。  
> 著作権上の制約から、原文引用は定義・核心箇所の短いフレーズに限定し、それ以外は正確な要約で補っています。

---

## ① Sharpe (1964)

**書誌情報**  
Sharpe, W.F. (1964). "Capital Asset Prices: A Theory of Market Equilibrium under Conditions of Risk." *Journal of Finance*, 19(3), 425–442.

### 主張の核心

リスクプレミアムは「分散不能なシステマティックリスク（ベータ）のみに対して支払われるもの」である。投資家はリスク回避的であり、市場ポートフォリオへの感応度（β）に比例した超過リターンを要求する。個別リスクは分散投資によって消去できるため、補償の対象とならない。

### 原文（核心箇所）

> *"Investors are assumed to prefer a higher expected future wealth to a lower value, ceteris paribus. Moreover, they exhibit risk-aversion, choosing an investment offering a lower value of σ to one with a greater level, given the level of expected return."*

> *"The expected return on any asset is equal to the risk free rate plus a risk premium given by the product of [beta and the market risk premium]."*  
> （Jensen 1968 による Sharpe 1964 の定式化の要約）

---

## ② Lintner (1965)

**書誌情報**  
Lintner, J. (1965). "Security Prices, Risk, and Maximal Gains from Diversification." *Journal of Finance*, 20(4), 587–615.

### 主張の核心

個別証券のリスクプレミアムは、標準偏差ではなく**分散・共分散**（ポートフォリオへの限界的リスク寄与）によって決まる。「リスクプレミアムはリスクの標準偏差に線形比例する」という従来の直感を修正した点が最大の貢献である。リスク回避的な投資家がリスクフリー資産を持てる状況を前提に、この結論を導出している。

### 原文（核心箇所）

> *"Although the general presumption in the literature has been that 'risk premiums' on securities should vary linearly with their risk as measured by the standard deviation of their return, it thus turns out that the relevant measure of the risk of an individual security within a portfolio of risk assets is given by its return-variance and covariance (with other securities)."*

---

## ③ Mehra & Prescott (1985)

**書誌情報**  
Mehra, R., & Prescott, E.C. (1985). "The Equity Premium: A Puzzle." *Journal of Monetary Economics*, 15(2), 145–161.  
（関連論文：Mehra, R. (2003). "The Equity Premium: Why Is It a Puzzle?" NBER Working Paper No. 9512.）

### 主張の核心

歴史的な株式リスクプレミアム（約7%）は、標準的な消費ベースの経済モデルでは到底説明できないほど大きい（「株式プレミアムパズル」）。理論的には、リスクプレミアムの本質を**消費の限界効用**の観点から定義している。すなわち、景気が悪いとき（消費が低く限界効用が高いとき）に悪いパフォーマンスをとる資産は、より高いプレミアムを要求されるという原理を示している。

### 原文（リスクプレミアムの定義と実証値）

> *"The historical U.S. equity premium (the return earned by a risky security in excess of that earned by a relatively risk free U.S. T-bill) is an order of magnitude greater than can be rationalized in the context of the standard neoclassical paradigm of financial economics."*

> *"The average annual real return on the U.S. stock market for the past 110 years has been about 7.9 percent. In the same period, the real return on a relatively riskless security was a paltry 1.0 percent. The difference between these two returns, 6.9 percentage points, is the equity premium."*

### 原文（リスクプレミアムの理論的説明）

> *"Assets that pay off when times are good and consumption levels are high, i.e. when the incremental value of additional consumption is low, are less desirable than those that pay off an equivalent amount when times are bad and additional consumption is both desirable and more highly valued."*

---

## ④ Fama & French (1993)

**書誌情報**  
Fama, E.F., & French, K.R. (1993). "Common Risk Factors in the Returns on Stocks and Bonds." *Journal of Financial Economics*, 33(1), 3–56.

### 主張の核心

CAPMの単一ベータでは株式のリターン断面分布を説明できない。**規模（SMB：小型株マイナス大型株）**と**バリュー（HML：高BEMEマイナス低BEME）**の2ファクターは、それぞれ独立したリスクプレミアムの源泉である。市場が合理的である限り、これらの変数は共通の未分散化リスクへの感応度を代理している。また、株式リターンと債券リターンを統合的に説明できる5ファクターモデルを提示した。

### 原文（アブストラクト）

> *"This paper identifies five common risk factors in the returns on stocks and bonds. There are three stock-market factors: an overall market factor and factors related to firm size and book-to-market equity. There are two bond-market factors, related to maturity and default risks… Most important, the five factors seem to explain average returns on stocks and bonds."*

### 原文（リスクプレミアムの理論的位置づけ）

> *"If assets are priced rationally, variables that are related to average returns, such as size and book-to-market equity, must proxy for sensitivity to common (shared and thus undiversifiable) risk factors in returns."*

---

## ⑤ Damodaran（毎年更新）

**書誌情報**  
Damodaran, A. (2026). "Equity Risk Premiums (ERP): Determinants, Estimates and Implications – The 2026 Edition." SSRN Working Paper.  
（初版：1999年。以降毎年更新。最新版：https://ssrn.com/abstract=6361419）

### 主張の核心

リスクプレミアムは「リスクをどのように期待リターンに換算するか」という問いの中心にある実務的パラメータである。歴史的リターン法・インプライドERP法・サーベイ法という三つのアプローチを体系化し、実務における計測の不統一性を批判的に整理している。特にインプライドERPをもっとも概念的に優れた手法と位置づける。また、歴史的手法には標準誤差・生存者バイアス・リスクフリーレートの選択など多くの落とし穴があることを詳述している。

### 原文（冒頭定義）

> *"The notion that risk matters, and that riskier investments should have a higher expected return than safer investments, to be considered good investments, is intuitive. Thus, the expected return on any investment can be written as the sum of the riskfree rate and an extra return to compensate for the risk. The disagreement, in both theoretical and practical terms, remains on how to measure this risk, and how to convert the risk measure into an expected return that compensates for risk."*

### 原文（歴史的手法の限界）

> *"The standard approach to estimating equity risk premiums remains the use of historical returns… We note the limitations of this approach, even in markets like the United States, which have long periods of historical data available, and its complete failure in emerging markets, where the historical data tends to be limited and noisy."*

---

## ⑥ Duarte & Rosa (2015)

**書誌情報**  
Duarte, F., & Rosa, C. (2015). "The Equity Risk Premium: A Review of Models." *Federal Reserve Bank of New York Staff Report*, No. 714.  
（入手先：https://www.newyorkfed.org/medialibrary/media/research/staff_reports/sr714.pdf）

### 主張の核心

リスクプレミアムは単一のモデルで精確に計測することが困難であり、20種類のモデル（歴史的平均・配当割引モデル・時系列回帰・横断面回帰・サーベイ）を統合することで初めて信頼ある推定が得られる。リスクプレミアムは「集計的なリスク回避度の指標」であり、資本コストや家計の貯蓄行動、政府の予算計画にも影響する根本変数として位置づけられる。2012〜2013年のERPが1970年代以来の高水準（約12%）に達した主因が、国債利回りの異常な低下にあることを実証した。

### 原文（定義と位置づけ）

> *"The equity risk premium —the expected return on stocks in excess of the risk-free rate— is a fundamental quantity in all of asset pricing, both for theoretical and practical reasons. It is a key measure of aggregate risk-aversion and an important determinant of the cost of capital for corporations, savings decisions of individuals and budgeting plans for governments."*

> *"Conceptually, the ERP is the compensation investors require to make them indifferent at the margin between holding the risky market portfolio and a risk-free bond."*

---

## まとめ対照表

| 論文 | リスクプレミアムの定義 | 計測の方針 |
|---|---|---|
| Sharpe (1964) | β（市場感応度）への補償 | 市場ポートフォリオとの共変動 |
| Lintner (1965) | 共分散リスクへの補償 | 分散・共分散行列から算出 |
| Mehra & Prescott (1985) | 消費の限界効用リスクへの補償 | 実現リターンの長期平均差 |
| Fama & French (1993) | 複数の未分散化リスクへの補償 | ファクターポートフォリオのリターン差 |
| Damodaran（継続） | リスクをリターンに換算するパラメータ | 3手法（歴史・インプライド・サーベイ）の比較 |
| Duarte & Rosa (2015) | リスク回避度の市場価格 | 20モデルの主成分合成 |

---

*注：原文引用は著作権保護論文の核心的なフレーズのみを短く抜粋したものです。各論文の全文はJSTOR・Wiley Online Library・SSRN・各機関リポジトリ等から入手してください。*
