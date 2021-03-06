### 0. About myself

```markdown
- Preparer: Chen, Weiyi
- Bachelor: Tsinghua Univ, CS
- Master: Baruch College, FE
- Contacts: weiyi.alan.chen@gmail.com, chenweiyi662109
```

### 1. What is Financial Engineering?

"The application of science-based mathematical models to decisions about saving, investing, borrowing, lending, and managing risk."

<img src="https://previews.123rf.com/images/radiantskies/radiantskies1212/radiantskies121201630/16719564-Abstract-word-cloud-for-Financial-engineering-with-related-tags-and-terms-Stock-Photo.jpg" width="400">
<img src="http://thompsonenterprisesltd.com/wp-content/uploads/2015/03/Thompson_Engineering_Decision_and_Financial_Engineering_Group.jpg" width="400">

Financial engineering is applicable to -

#### 1.1 derivatives pricing

<img src="http://i.investopedia.com/inv/dictionary/terms/optvalue_0606.gif">
<img src="https://static1.squarespace.com/static/5371c4c9e4b0cb63d6f51baf/t/537f7b00e4b00c859fe19c2d/1400863498603/">

#### 1.2 financial regulation

<img src="http://harvardpolitics.com/blog/wp-content/uploads/2009/12/0-cover.jpg" width="400">
<img src="http://www.biia.net/wp-content/uploads/2010/12/010-Media-Regulations-in-China.jpg" width="400">

#### 1.3 execution

<img src="http://www.esignal.com/medias/2015/10/options-analytix-beauty.png" width="800">

#### 1.4 corporate finance

<img src="http://www.ulalocapital.com/wp-content/uploads/2015/12/corporate-finance-finalxz.jpg" width="800">

#### 1.5 portfolio management 
([Portfolio Visualizer Link](https://www.portfoliovisualizer.com/optimize-portfolio#analysisResults))

#### 1.6 risk management 
([Quantopian Risk Metrics](https://www.quantopian.com/posts/stocks-on-the-move-by-andreas-clenow))

#### 1.7 trading

<img src="https://www.etnasoft.com/wp-content/uploads/2012/12/Front-Office.png" width="800">

#### 1.8 structured products.

<img src="https://www.citibank.com.au/aus/images/investment/understanding-structured-products.png" width="800">

### 2. Financial Engineering Career Overview

The financial engineers are specialists making use of mathematical formulas, programming and engineering methods in financial theories, and analyses market trends to build data-backed financial models.

#### 2.1 Jobs

Companies often employ people with advanced degree in Financial Engineering and these specialists work as **quants**, **traders**, **portfolio managers**, **structurers** or **bankers** using their financial engineering background to improve the quality of existing investment products.

#### 2.2 Primary responsibility (quants / traders)

The primary responsibility of a financial engineer is to have thorough knowledge of financial markets, its volatility and knowledge of financial theories. This knowledge is used by engineers to develop simulations and predict market behaviour.

![Vol Surface](https://www.mathworks.com/matlabcentral/mlc-downloads/downloads/submissions/23316/versions/2/screenshot.jpg)
![Monte Carlo](https://s-media-cache-ak0.pinimg.com/originals/69/b6/d6/69b6d6e998ba9f30cff1950859234446.png)

Apart from knowledge in finance, the engineer needs to possess sufficient computer programming skills. Programming skills are needed to build simulating financial models to learn about market behavior.

#### 2.3 Financial risk management (risk / portfolio managers)

With the knowledge of computer simulations and market trends, the engineer helps to develop profitable investment plans for individuals and companies. Often, these investment plans have high risk factor, which might seem counter-productive to the goal of hiring financial engineers, but that’s a strategy used by risk management firms to yield higher return than comparatively stable investments. 

### 3. Preparing for Financial Engineering Career: Education

#### 3.1 Quanlifications 

A Bachelors’ in Science, a Master’s in Science or a Masters’ in Financial Engineering (MFE) will gear you towards quantitative roles such as delivering risk models and trading directly, library control, model validation, risk management and programming.

#### 3.2 PhD?

Many of the financial engineers don’t hold PhD as some employers feel the degree will have detrimental impact. A Masters’ degree in computer engineering and electrical engineering with strong programming skills and data handling ease is recommended.

Mathematical geniuses can go for PhD. Knowledge in programming like SAS, MATLAB, S+ or RAD or other statistical packages will place you at a disadvantage as higher advanced languages like Java and Scala are used.

#### 3.3 Market Demand?

There is a high need for qualified quants in the market. The demand for new quants is particularly high in **structured finance** establishments. Over time, as the market gains higher traction, the demand for quants will increase. Emphasis will be on credit and risk ventures.

Moreover, the world of **systematic, quantitative, algorithmic and automated trading** offers various openings for quants.

The level of competition is high for entry-level quants as they need to display programming skills, **knowledge of artificial intelligence methods and statistical theories**. Good experience with languages like **Python, Java, C++** and Scala is essential for financial engineering.

#### 3.4 Employers

- [Investment Banks](https://en.wikipedia.org/wiki/List_of_investment_banks) 
- [Hedge Funds](https://en.wikipedia.org/wiki/List_of_hedge_funds)
- [Asset Management Firms](https://en.wikipedia.org/wiki/List_of_asset_management_firms)

### 4. Preparing for Financial Engineering Career: Skills

#### 4.1 Communication skills

- Anyone working as a financial engineer is ‘smart’ and the only reason why some people move ahead in the career ladder is because of their articulate communicative nature. 
- You don’t need to be a refined public speaker but have the ability to communicate thoughts and ideas clearly.

#### 4.2 Programming

- C++
- Python
- Java
- MATLAB
- Hadoop
- C#
- .NET
- Perl

```python
def initialize(context):
    context.security = symbol('AAPL')
    schedule_function(myfunc, date_rules.every_day(),  time_rules.market_open(minutes = 15))

def handle_data(context, data):
    MovingAvg1 = data[context.security].mavg(10)
    MovingAvg2 = data[context.security].mavg(30)
    
    current_positions = context.portfolio.positions[symbol('AAPL')].amount
    
    if (MovingAvg1 > MovingAvg2) and current_positions == 0:
        order_target_percent(context.security, 0.25)
            
    elif (MovingAvg1 < MovingAvg2) and current_positions != 0:
        order_target(context.security, 0)
```

#### 4.3 Mathematics

- linear algebra
- stochastic calculus
- geometry
- differential equations

#### 4.4 Econ and Finance

Finance and economics aren’t that important in quantitative trading, other than giving the professional a well-developed approach towards the finance markets. 

### 5. Job Market 

- The median salary of financial engineers in USA is 91,330 USD.

![Salary Range](http://www.financewalk.com/wp-content/uploads/2015/02/Salary-Range.png)

- The data below shows how experience impacts the salary scale of financial engineers.

![Experience Scale](http://www.financewalk.com/wp-content/uploads/2015/02/Experience.png)

- In gender ratio, 21% and 79% are the figures of female and male financial engineers.

![Gender And Experience](http://www.financewalk.com/wp-content/uploads/2015/02/Gender-and-Experience.png)

### 6. Quant Types

Quantitative positions within finance can be broadly categorised into four main types. 

#### 6.1 Quantitative Trader

- Employer: a bank (prop trading desk), a quantitative/systematic hedge fund
- Responsibility: alpha, the elusive returns above those returned as a component of standard stock market fluctuations
- Skills: statistical or machine-learning
- Package: $200K

![Trader](./Trader.png)

#### 6.2 Quantitative Researcher

- Employer: a bank (research desk, middle-office), alternative research firms, some larger hedge funds
- Skills: a pure mathematician or PhD in stochastic calculus
- Package: $180k (associate)

![Trader](./Researcher.png)

#### 6.3 Desk Quants

Tasked with taking a product (FICC, Equity), often sold by sales teams to clients within large banks, and figuring out how to correctly price it. Business:

1. Foreign Exchange
2. Interest rate
3. Commodity
4. Credit
5. Equity
6. Mortgage

- Employer: bank (market making desks, front-office)
- Skills: stochastic calculus, risk-neutral pricing, strong/fast programming
- Package: $120k (analyst) $180k (associate)

![Trader](./Analyst.png)

#### 6.4 Quantitative Developer

First type: work closely with desk quantits to implement and optimise their financial models, taking a prototype code from R or Python and rewriting it in another language such as C++ or Java

- Employer: bank (market making desks, front-office)
- Skills: programming
- Package: base similar to quants, bonus less

Second type: deal with financial pricing data and trading systems architecture, code up the raw infrastructure allowing the quant analysts/traders to run their models on and make money

- Employer: bank (middle-office), fund
- Skills: programming, large-scale legacy systems
- Package: eh..

Third type: star C/C++ developer who understands Unix network programming, low-latency systems and the ins and outs of the Linux Kernal

- Employer: Ultra High-Frequency Trading (UHFT)
- Skills: Unix network programming, distributed systems, Linux systems, parallel/threads programming
- Package: $300+k

![Trader](./Developer.png)

