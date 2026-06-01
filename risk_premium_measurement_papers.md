# リスクプレミアムの実務的計測に関する主要論文

> 本稿では、リスクプレミアムを実務的にどのように計測するかを論じた、あるいは実際に計測した論文・サーベイをまとめる。
> 計測手法ごとに整理し、各論文の主張と核心的な原文（英語）を併記する。
> 著作権上の制約から、原文引用は定義・核心箇所の短いフレーズに限定し、それ以外は正確な要約で補っている。

---

## 計測手法の全体像

リスクプレミアムの実務的計測は、大きく以下の5手法に分類される。

| 手法 | 概要 |
|---|---|
| ① 歴史的リターン法 | 過去の株式・国債リターン差の平均を将来の期待値とする |
| ② サプライサイド法 | GDP・利益・配当などマクロ要因からボトムアップで推計する |
| ③ インプライドERP法 | 現在の市場価格から期待リターンを逆算する |
| ④ サーベイ法 | 実務家・研究者への直接調査で期待値を収集する |
| ⑤ タームプレミアム計測 | 利回り曲線から期間リスクプレミアムをモデルで分離する |

各手法を代表する論文を以下に論じる。

---

## 手法①：歴史的リターン法（Historical Approach）

### 1. Ibbotson & Sinquefield (1976)

**書誌情報**
Ibbotson, R.G., & Sinquefield, R.A. (1976). "Stocks, Bonds, Bills, and Inflation: Year-by-Year Historical Returns (1926–1974)." *Journal of Business*, 49(1), 11–47.

**主張の核心**

米国株式・長期国債・短期国債・インフレの1926年以降の年次リターン系列を初めて体系的にデータベース化した論文。歴史的リターン差（株式マイナス国債）をリスクプレミアムの代理変数として用いる「ビルディングブロック・アプローチ」の出発点。実務上はIbbotsonデータとして広く参照され、後にMorningstar/Duff & Phelpsが引き継いで毎年更新している。リスクプレミアムは各資産クラスのリターン格差の積み上げ（building blocks）で説明されるという考え方が、コーポレートファイナンスと証券分析の双方で定着した。

**原文（アブストラクトおよび本文冒頭）**

> *"We present a comprehensive history of returns on United States capital markets from 1926 through 1974 for stocks, long-term government bonds, long-term corporate bonds, U.S. Treasury bills, and consumer price index changes."*

> *"The equity risk premium is obtained by subtracting returns on relatively riskless short-term securities from the returns on stocks."*

---

### 2. Dimson, Marsh & Staunton (2002・毎年更新)

**書誌情報**
Dimson, E., Marsh, P., & Staunton, M. (2002). *Triumph of the Optimists: 101 Years of Global Investment Returns.* Princeton University Press.
（毎年 *Global Investment Returns Yearbook* として更新。2025年版はUBSより公表。）

**主張の核心**

20カ国超・1900年以降の株式・国債・短期証券・インフレデータを、生存者バイアスを排除した形で構築・分析した大著。主要な計測上の問題点として「生存者バイアス」（過去に存在した国・市場が失敗したものも含めて評価すべき）と「過去の米国の例外性」を強調し、単純な歴史的平均は将来のリスクプレミアムを過大推計する可能性があると主張する。幾何平均での世界平均株式リスクプレミアムは3〜4%程度と推計。規制機関・年金基金が世界的に参照する標準ベンチマークとなっている。

**原文（SSRN版より）**

> *"Investors have too often extrapolated from the American experience and from relatively recent evidence… We present a comprehensive and consistent analysis of investment returns for equities, bonds, bills, currencies, and inflation, spanning sixteen countries from the end of the nineteenth century to the beginning of the twenty-first. Our indexes are chosen to avoid survivorship bias, and all returns include reinvested income."*

> *"Between 1900 and 2000, equities were by far the highest-performing asset class compared to bonds or money market papers. On a global basis, shareholders achieved an annual return of 5.1%. The risk-free money market, in contrast, generated 0.8% per year while bonds generated 1.8%."*

---

## 手法②：サプライサイド法（Supply-Side Approach）

### 3. Ibbotson & Chen (2003)

**書誌情報**
Ibbotson, R.G., & Chen, P. (2003). "Long-Run Stock Returns: Participating in the Real Economy." *Financial Analysts Journal*, 59(1), 88–98.

**主張の核心**

過去のリターンをそのまま将来に延長するのではなく、リターンを構成するサプライサイド要因（インフレ・一株当たり利益・配当・P/E・配当性向・ROE・GDP成長率）に分解し、各要因を経済実態に照らして予測することでフォワードルッキングなリスクプレミアムを推計する手法を提唱。P/Eの上昇はリターンの一時的なかさ上げ要因に過ぎず、持続的なリターンの源泉はGDP成長率と連動した利益・配当成長にあると主張。純粋な歴史的リターン推計よりわずかに低い、幾何平均約4%・算術平均約6%のリスクプレミアムを推計した。

**原文（アブストラクトおよび本文）**

> *"We estimated the forward-looking long-term equity risk premium by extrapolating the way it has participated in the real economy. We decomposed the 1926–2000 historical equity returns into supply factors—inflation, earnings, dividends, the P/E, the dividend-payout ratio, book value, return on equity, and GDP per capita."*

> *"P/E increases account for only a small portion of the total return of equity. The bulk of the return is attributable to dividend payments and nominal earnings growth (including inflation and real earnings growth)."*

> *"We estimate the expected long-term equity risk premium (relative to the long-term government bond yield) to be about 6 percentage points arithmetically and 4 percentage points geometrically."*

---

## 手法③：インプライドERP法（Implied / Forward-Looking Approach）

### 4. Damodaran（1999〜毎年更新）

**書誌情報**
Damodaran, A. (2026). "Equity Risk Premiums (ERP): Determinants, Estimates and Implications – The 2026 Edition." SSRN Working Paper. https://ssrn.com/abstract=6361419
（初版1999年。以降毎年更新。）

**主張の核心**

リスクプレミアムの計測手法を（1）歴史的リターン法、（2）インプライドERP法、（3）サーベイ法の3つに分類し、各手法の長所・短所を体系的に論じる実務の標準参照論文。最も概念的に優れた手法としてインプライドERP法（DCFモデルから期待リターンを逆算する）を推奨する。歴史的手法については、時間軸の選択・リスクフリーレートの選択・算術vs幾何平均の選択という三つの問題により推計値に大きな幅が生じると批判する。また毎月インプライドERPを更新公表しており、米国については4〜5%程度が直近の水準。

**原文（定義と手法批判）**

> *"The notion that risk matters, and that riskier investments should have a higher expected return than safer investments, to be considered good investments, is intuitive. Thus, the expected return on any investment can be written as the sum of the riskfree rate and an extra return to compensate for the risk. The disagreement, in both theoretical and practical terms, remains on how to measure this risk, and how to convert the risk measure into an expected return that compensates for risk."*

> *"The standard approach to estimating equity risk premiums remains the use of historical returns… We note the limitations of this approach, even in markets like the United States, which have long periods of historical data available, and its complete failure in emerging markets, where the historical data tends to be limited and noisy."*

> *"The risk premium estimates vary across users because of differences in time periods used, the choice of treasury bills or bonds as the riskfree rate and the use of arithmetic as opposed to geometric averages."*

---

## 手法④：サーベイ法（Survey Approach）

### 5. Graham & Harvey（2001〜継続）

**書誌情報**
Graham, J.R., & Harvey, C.R. (2001). "Expectations of Equity Risk Premia, Volatility and Asymmetry from a Corporate Finance Perspective." NBER Working Paper No. 8678.
（以後 *The Equity Risk Premium in [Year]* として毎年更新。最新はSSRN参照。）

**主張の核心**

Duke大学が2000年第2四半期から実施する四半期CFOサーベイ。10年国債対比・10年ホライズンで期待する株式リスクプレミアムを収集し、同時に意見分散（不確実性）・歪度・個人信頼区間も計測する。主な発見は以下の3点。第一に、10年ホライズンのリスクプレミアムは約4%程度で比較的安定している。第二に、1年ホライズンは時変性が高く、過去のリターンが負の時期にCFOは将来見通しを大幅に下方修正する。第三に、金融危機時にはリスクプレミアムが急上昇し、VIX指数や信用スプレッドと強く連動する。CFOという実際に資本コストを算定する立場にある者の期待値を直接計測する点で、他のサーベイと一線を画す。

**原文（主要な発見）**

> *"We find direct evidence that the 10-year expected risk premium is stable and equal to about 4%. In contrast, the one-year risk premium is highly variable through time. In particular, after periods of negative returns, CFOs significantly reduce their one-year market forecasts, disagreement (volatility) increases and returns distributions are more skewed to the left."*

> *"We find a significantly positive relation between expected return and expected risk at the 10-year horizon."*

> *"Our analysis suggests the level of the risk premium closely tracks both market volatility (reflected in the VIX index) as well as credit spreads."*

---

### 6. Fernández et al.（2008〜毎年更新）

**書誌情報**
Fernández, P., García de la Garza, D., & Fernández Acín, L. (2025). "Survey: Market Risk Premium and Risk-Free Rate used for 54 countries in 2025." IESE Business School Working Paper. https://ssrn.com/abstract=5260463
（2008年以降毎年更新。リンクから過去年次版にアクセス可能。）

**主張の核心**

IESEビジネススクールが年次で実施する世界最大規模のリスクプレミアム実態調査。学術研究者・コンサルタント・アナリスト・実務家を対象に、各国で実際に使用されているMRP（市場リスクプレミアム）とリスクフリーレートを収集する。2024年調査では96カ国・6,000名超から回答を得た。重要な主張として、「期待MRP」「要求MRP」「歴史的MRP」「インプライドMRP」の4概念が混同されがちであることを指摘し、その区別が不可欠であると強調する。また、MRPに「正解」は一つではなく、投資家・国・用途によって異なると結論づけている。米国の平均MRPは直近調査で約5.5%。

**原文（アブストラクト）**

> *"This paper contains the statistics of a survey about the Risk-Free Rate (RF) and the Market Risk Premium (MRP) used in 2025 for 54 countries. We got answers for 103 countries, but we only report the results for 54 countries with more than 6 answers. The paper also contains the links to previous years surveys, from 2008 to 2024."*

**原文（概念整理に関する主張、2023年版より）**

> *"Much confusion arises from not distinguishing among the four concepts that the phrase equity premium designates: Historical equity premium, Expected equity premium, Required equity premium and Implied equity premium."*

---

## 手法⑤：タームプレミアム計測（Term Premium Models）

### 7. Adrian, Crump & Moench (2013)

**書誌情報**
Adrian, T., Crump, R.K., & Moench, E. (2013). "Pricing the Term Structure with Linear Regressions." *Journal of Financial Economics*, 110(1), 110–138.
（元論文：NY Fed Staff Report No. 340, 2008/revised 2013。データは NY Fed ウェブサイトから無償公開。）

**主張の核心**

アフィン・ダイナミックタームストラクチャーモデル（DTSM）の推計を、従来の最尤法（MLE）に代わる3ステップ最小二乗（OLS）回帰で行う手法（ACMモデル）を提案した。第1ステップで利回り主成分の自己回帰を推計、第2ステップで債券リターンの要因感応度を推計、第3ステップでリスク価格を横断面回帰で推定することで、タームプレミアム（長期債保有の期間リスクへの補償）をイールドカーブから分解する。5つの利回り主成分を用いたモデルが最良であることを示し、Cochrane-Piazzesi（2008）の4ファクターモデルをアウト・オブ・サンプルで上回ることを実証した。現在はFRB・日本銀行・ECBをはじめ世界の中央銀行・機関投資家の標準的なタームプレミアム計測ツールとなっている。

**原文（アブストラクト）**

> *"We show how to price the time series and cross-section of the term structure of interest rates using a three-step linear regression approach. Our method allows computationally fast estimation of term structure models with a large number of pricing factors. We present specification tests favoring a model using five principal components of yields as factors. We demonstrate that this model outperforms the Cochrane and Piazzesi (2008) four-factor specification in out-of-sample exercises but generates similar in-sample term premium dynamics."*

**原文（手法の位置づけ）**

> *"We start with observable pricing factors and develop a three-step ordinary least squares (OLS) estimator. In the first step, we decompose pricing factors into predictable components and factor innovations by regressing factors on their lagged levels. In the second step, we estimate exposures of Treasury returns with respect to lagged levels of pricing factors and contemporaneous pricing factor innovations. In the third step, we obtain the market price of risk parameters from a cross-sectional regression."*

---

## 総括：計測手法の批判的評価

### 8. Goyal & Welch (2008)

**書誌情報**
Goyal, A., & Welch, I. (2008). "A Comprehensive Look at the Empirical Performance of Equity Premium Prediction." *Review of Financial Studies*, 21(4), 1455–1508.

**主張の核心**

配当利回り・P/E比・利益成長率・ペイアウト比率・帳簿価格比率・各種金利・インフレ率・消費・富・所得比（cay）など、学術文献が提案してきた多数のリスクプレミアム予測変数を網羅的かつ統一的な手法で再検証した。結論は厳しく、（1）これらのモデルの多くはサンプル内でさえ過去30年間にわたって予測力が低下している、（2）サンプル外予測はさらに悪化しており不安定である、（3）投資家がリアルタイムで使用可能な情報だけを使っても市場タイミングには役立たなかった、というものである。リスクプレミアムの時変性を捉えようとする実証研究の困難さを徹底的に示した論文として、引用数1,000件超の重要文献。

**原文（アブストラクト）**

> *"Our article comprehensively reexamines the performance of variables that have been suggested by the academic literature to be good predictors of the equity premium. We find that by and large, these models have predicted poorly both in-sample (IS) and out-of-sample (OOS) for 30 years now; these models seem unstable, as diagnosed by their out-of-sample predictions and other statistics; and these models would not have helped an investor with access only to available information to profitably time the market."*

**原文（予測変数の概要）**

> *"The most prominent x variables explored in the literature are the dividend price ratio and dividend yield, the earnings price ratio and dividend-earnings (payout) ratio, various interest rates and spreads, the inflation rates, the book-to-market ratio, volatility, the investment-capital ratio, the consumption, wealth, and income ratio, and aggregate net or equity issuing activity."*

---

### 9. Duarte & Rosa (2015)

**書誌情報**
Duarte, F., & Rosa, C. (2015). "The Equity Risk Premium: A Review of Models." *Federal Reserve Bank of New York Staff Report*, No. 714.
https://www.newyorkfed.org/medialibrary/media/research/staff_reports/sr714.pdf

**主張の核心**

20の主要なERP計測モデルを（1）歴史的平均、（2）配当割引モデル（DDM）、（3）横断面回帰、（4）時系列回帰、（5）サーベイの5カテゴリに分類し、第1主成分分析によって統合推計を行った。2012〜2013年のERPが約12%と1970年代以来の高水準に達した要因が、期待株式リターンの上昇ではなく国債利回りの異常な低下にあると結論づける。この発見は、P/E比や配当利回りなど金利情報を含まない従来の指標がERPの先行指標としての有効性を失いつつある可能性を示唆する。各計測手法の前提・データ・限界を体系的に比較した最良のサーベイ論文の一つ。

**原文（定義と位置づけ）**

> *"The equity risk premium —the expected return on stocks in excess of the risk-free rate— is a fundamental quantity in all of asset pricing, both for theoretical and practical reasons. It is a key measure of aggregate risk-aversion and an important determinant of the cost of capital for corporations, savings decisions of individuals and budgeting plans for governments."*

> *"Conceptually, the ERP is the compensation investors require to make them indifferent at the margin between holding the risky market portfolio and a risk-free bond. Because this compensation depends on the future performance of stocks, the ERP incorporates expectations of future stock market returns, which are not directly observable. At the end of the day, any model of the ERP is a model of investor expectations."*

> *"We conclude that the high ERP was caused by unusually low Treasury yields. Current and expected future dividend and earnings growth play a smaller role."*

---

## 論文対照表

| 手法 | 論文 | 掲載誌・媒体 | 計測の核心 | 推計値（米国） |
|---|---|---|---|---|
| 歴史的リターン | Ibbotson & Sinquefield (1976) | *Journal of Business* | 株式・国債リターン差の長期平均 | 約6〜8%（算術） |
| 歴史的リターン（国際） | Dimson, Marsh & Staunton (2002〜) | Princeton UP / UBS Yearbook | 23カ国・125年・生存者バイアス排除 | 約3〜4%（幾何） |
| サプライサイド | Ibbotson & Chen (2003) | *Financial Analysts Journal* | GDP・利益・配当成長からの積み上げ | 約4%（幾何）/ 約6%（算術） |
| インプライドERP | Damodaran (毎年) | SSRN / NYU Stern | DCFモデルによる市場価格からの逆算 | 約4〜5%（直近） |
| サーベイ（CFO） | Graham & Harvey (2001〜) | NBER WP / SSRN | 米国CFOへの四半期調査 | 約3〜5%（時変） |
| サーベイ（多国間） | Fernández et al. (2008〜) | SSRN / IESE | 100カ国超・年次実務家調査 | 約5.5%（2024年） |
| タームプレミアム | Adrian, Crump & Moench (2013) | *Journal of Financial Economics* | 3ステップOLS・イールドカーブ分解 | 時系列公開（NY Fed） |
| 総合評価 | Goyal & Welch (2008) | *Review of Financial Studies* | 予測変数の網羅的再検証 | 予測困難性を実証 |
| 総合レビュー | Duarte & Rosa (2015) | NY Fed Staff Report | 20モデルの主成分統合推計 | 2012〜13年：約12% |

---

*注：原文引用は著作権保護論文の核心的フレーズのみを短く抜粋したものです。全文はSSRN・各機関リポジトリ・学術誌データベース等からご入手ください。*
