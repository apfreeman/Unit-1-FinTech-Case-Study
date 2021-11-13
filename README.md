# Unit 1 Homework Assignment: FinTech Case Study ***Volante***

![Volante](https://assets.volantetech.com/assets/images/volante-logo.png)


## Company Information and Business Activities
### Volante FinTech Domain
A FinTech professional needs to have an understanding of the wider FinTech landscape and understand who are the incumbent, emerging and leading players within this field. It is expected that a FinTech professional is able to seek out technology that may be useful to solve a financial problem or disrupt existing methods of operation. The financial sector is notorious for technology that is critical to business operation but in many cases is bound by technology limitations at the time of implementation. Many technological advances have opened the door to infinite applications of cutting edge technology which can form significant disrupter and enablers across the whole FinTech domain. 

While there are many domains across the FinTech landscape, this case study will specifically target the ***Payments/Billing*** domain. The company identified within this FinTech domain is ***Volante***, This FinTech company will form the target of this case study, and more specifically target the ***Volante VoIPay Solution***.  

The Volante VoIPay solution provides End to End payment processing for its customers. This essentially provides a standard technology agnostic entry point for large enterprise to process the movement of funds. This removes the requirement for large organisations to manage and maintain their own myriad of proprietary payment processing systems and solutions.     

### Intended Audience
The intended customer for this solution are large enterprise scale financial institutions. Volante is the leading global provider of cloud payments and financial messaging solutions. Volante serves as a trusted partner to over 100 banks, financial institutions, market infrastructures, clearing houses and corporate treasuries in 35 countries. Volante solutions and services process millions of transactions and trillions in value every day, powering four of the top five corporate banks, 40% of all US commercial bank deposits, and 70% of worldwide card traffic.

### Solution
There are many companies providing the types of financial technology based services that Volante offer. The most notable point difference over its competitors is in their key product VoIPay. This solution is an Enterprise grade set of business services for payment modernisation built utilising the latest technologies for service hosting and integration. By using these modern services the Volante VoIPay system has inherent resiliency, scalability and security to support all the way up to the most tightly regulated enterprise grade consumers. The Volante VoIPay solution also has an edge over its competitors in that it can provide multiple models of deployment, these include On-Premise, As a Service, Private Cloud, Public Cloud and Hybrid. For example, some of Volante's competitors provide a SaaS only model. This can preclude their solution from being adopted by some customers with very strictly data sovereignty rules or who require customised security, reporting or integration methods to comply with specific regulations. VoIPay sets Volante apart as a high performing, highly customisable, highly interoperable, highly available platform that can tick in most cases all the boxes required by the most demanding enterprise grade customers. While the solution is highly resilient and scalable it is also provides modern and secure methods for integration. Volante VoIPay has invested heavily in API development enabling a standard entry and integration point between VoIPay and legacy financial platforms. This type of integration essentially insulates both provider and consumer from change within either organisation. While consumer back end systems may change and develop so may the VoIPay platform. A consistent and stable API layer is exposed to the consumer and remains unchanged despite the changes in either back end. This is a very attractive architecture for consumers who are looking to streamline their integration and essentially reduce the cost of doing business.  

The Volante VoIPay service has been built as a Cloud-native MicroServices based solution. Using these technologies tells you a lot about how Volante is meet their communicated performance, availability and security metrics. The key technologies that have the most bearing on the VoIPay solution, and will be focussed on are
Azure MicroServices
Enterprise ESB
API Gateway
This is not a complete list by any stretch but are just the top 3 technologies utilised.
Volante is using Microsoft MicroServices in Azure to host the solution. By using MicroServices many of the fundamental storage, performance, networking and security requirements are inherently delivered. Azure MicroServices allow Volante to focus on the product and not spend time or worry about the physical infrastructure required to support the solution. The use of fabric clusters in Azure ensure that VoIPay MicroServices are elastic allowing them to dynamically scale up or down based on platform demand. Azure MicroServices are deployed across multiple and geo diverse nodes protecting the solution in event of disaster or unexpected down time in a particular data centre or location. Essentially the Microsoft Azure MicroServices stack is doing all the heavy lifting hosting this solution and ensuring it is available and able to meet performance requirements.

The next technology utilised by the Volante VoIPay solution is an ESB or Enterprise Service Bus. An ESB is all about integration and interoperability. The ESB in simple terms is a translation, queuing and messaging service between multiple applications or platforms. Due to the disparate technology the VoIPay system needs to integrate with for example banks, trading partners, wire transfers etc there needs to be a middleware that can translate, normalise and secure messages between these systems while ensuring delivery. Volante has provided standard interface libraries using Mule ESB. Mule ESB is a MuleSoft product which is a market leader in the Enterprise Service Bus space. 

The final technology examined in the case study that is utilised by the Volante VoIPay solution is API. API stands for application programming interface and is essentially a set of rules that govern the exchange of data. The VoIPay solution leverages RESTful API's to offer a set of standard integration points to customers. In simple terms the API layer of the Volante Solution provides and exposed integration point that is stable and consistent. Changes to the back end VoIPay system will occur over time but the exposed integration points will not. This essentially insulates external companies looking to utilise VoIPay services via API. The API calls will remain the same, even though what they do in the back end may change over time, this is not visible to the consumer. This model provides a consistent and streamlined integration that is secure and does not need to be recoded every time there is a system change. The Volante VoIPay system is currently delivering over 300+ APIs for open banking.

### Business Metrics

- 100+ Enterprise Customers
- 4 out of the 5 top corporate banks
- Servicing customers in 35 countries
- Processes 40% of all US commercial bank deposits
- Processes 70% of worldwide card traffic
- 46 Million transactions per hour
- $1.4tn processed by a single customer in a single day
- 300+ APIs developed for open banking
- 24x7x365 operation with zero downtime

## FinTech Domain Trends
### Trends and Landmarks

The Payments\Billing financial domain has seen large scale adoption of Cloud services to provide solution hosting, resilience and performance. These trends have relieved many companies of the burden of self hosting core services like storage, networking, platform hosting etc. This trend of "As a Service" consumption enables FinTech companies to focus on their core business and solution and not have to worry about infrastructure maintenance, security and hosting. The results of this is a much lower cost of entry and as such you are seeing many startups and new challengers to the incumbents within the Payments and Billing domain.

Other trends in this domain is the move away from closed source Legacy type solutions to open standards for integration and interoperability. Such examples include
- The use of enterprise service buses for translation, queuing, delivery and security for integration between services and platforms 
- Use of RESTful API to provide stable and consistent integration point

All these things have led to hugely capable solutions with infinite processing power enabling more automation and streamline of payment services. These trends in innovation have led to companies essentially outsourcing payment processing tasks rather then doing them in house. Physical dedicated infrastructure that was both costly to deploy, manage and maintain can now be deployed almost instantly in a manner of clicks. An example of this is for instance, develop a website on WIX, then select the option "add payment gateway". In under 15 minutes you can create a website and receive credit card payments using someone else's established infrastructure. This represents one of the biggest trends in FinTech payments and billing, focus on your core business and what you good at and let a FinTech company take care of the payment processing. 

### Major Competitors

While there are many companies playing in the Payment\Billing domain for example Stripe, Square, Paypal, WePaym Klarna, Checkout.com these are more focussed on direct customer facing billing and payment solutions. This case study is for focussed on orchestrating different types of payments between banks and corporate enterpises. As such the major companies in this space are 
- Infosys
- Finastra
- IBM
- SAP
- Oracle
- Finserv
- FIS

This is represented in the following anaysis completed by IDC MarkScape for WorldWide Integrated Payment Platforms 2019-2020

![](https://s3.us-east-1.amazonaws.com/volante-technologies/images/y3al26T1TKScQZWGpToQ-760w-idc-marketscape-hi-res-graphic-png)

#### SOURCE: IDC MarketScape: Worldwide Integrated Payment Platforms 2019-2020 Vendor Assessment, by Aaron Press , February 2020, IDC US46024520

## Research Depth
### Company History

Volante was founded in 2001 by Vijay Oddiraju, Uday Thakur and Venkat Malla. While serving as the CSO for NextSet, Vijay Oddiraju identified a market opportunity for technology to accelerate data transformation and integration in financial services. Volante operates as a Delaware offshore corporation and is a privately held. Volante has partnered with a number of companies who have invested financially to support the development and growth of this corporation. Investors in Volante include Visa, Wells Fargo, Citi Ventures, BNY Mellon, WaveCrest and Posteitaliane.

Since inception Volante has grown to be one of the most successful players in the Payments and Processing FinTech domain. Below summarises key milestone in Volante's growth, source references are linked to applicable milestones.

#### 2021
- [Volante Technologies Wins "Best Cloud Services Provider" at MEA Finance Awards 2021](https://www.prnewswire.co.uk/news-releases/volante-technologies-wins-best-cloud-services-provider-at-mea-finance-awards-2021-829703264.html)
- [Volante Technologies Named to The IDC FinTech Rankings 2021](https://www.prnewswire.com/news-releases/volante-technologies-named-to-the-idc-fintech-rankings-2021-301388799.html)
- [Wells Fargo Strategic Capital Brings Total Growth Investment in Volante Technologies to USD 45M](https://en.prnasia.com/releases/apac/wells-fargo-strategic-capital-brings-total-growth-investment-in-volante-technologies-to-usd-45m-337200.shtml)
- [Volante Launches Volante Experience™, Rapid Onboarding for Cloud Payments as a Service](https://www.volantetech.com/news-events/press-releases/volante-launches-volante-experience) 
- [Volante Continues Winning Streak by Coming First in the 2021 IBS Intelligence Sales League Table (SLT) for Wholesale Banking Payments](https://www.volantetech.com/news-events/press-releases/ibs-award)
- [Volante Wins “Most Innovative Payment Solutions Provider” at MEA Finance Banking Technology Awards 2021](https://www.volantetech.com/news-events/press-releases/mea-finance-award)
- [TAB Bank Rides Real-Time Payments Wave with Volante Technologies](https://www.volantetech.com/news-events/press-releases/tab-bank-real-time-payments)
- [Volante Wins CFI.co Best Payments & Financial Messaging Solutions Global Award](https://www.volantetech.com/news-events/press-releases/cfi-award)
- [Volante Joins FedNowSM Instant Payments Pilot Program](https://www.volantetech.com/news-events/press-releases/volante-to-help-shape-future-of-instant-payments)
- [Volante Extends Collaboration with Citi for Global ISO 20022 Migration](https://www.volantetech.com/news-events/press-releases/volante-extends-collaboration-with-citi-for-global-iso20022-migration)

#### 2020
- [Volante receives $35m in growth funding from Wavecrest Growth Partners, BNY Mellon, Citi Ventures, PostePay, and Visa Inc. to accelerate global cloud expansion](https://www.volantetech.com/news-events/press-releases/capital-raise)
- [IBS Intelligence names Volante a Wholesale Payment Systems Leader in their annual Sales League Table](https://www.volantetech.com/industry-recognition)
- [Volante recognized as a Leader in IDC MarketScape for Worldwide Integrated Payment Platforms](https://www.volantetech.com/news-events/press-releases/idc-marketscape)
- [First American Trust (US), Niche Global, and other leading banking providers deploy Volante's payment processing as a service in the cloud](https://www.volantetech.com/payments-as-a-service)

#### 2019
- [Volante Technologies named Global Winner, Best Payments Solution, by Global Finance Magazine](https://www.volantetech.com/news-events/press-releases/volante-technologies-named-global-winner-best-payments-solution-by-global-finance)
- [Banco BASE Mexico powers domestic and international payments processing with VolPay](https://www.volantetech.com/news-events/press-releases/volante-technologies-powers-banco-base-s-domestic-and-international-payments-processing)
- [Launch of Volante's SWIFT Message Validation Service in the cloud](https://www.volantetech.com/news-events/press-releases/swift-message-validation-service-on-the-cloud)
- [SEPA Instant Payments as a Service on Microsoft Azure for RT1 and TIPS released in Europe](https://www.volantetech.com/news-events/press-releases/volante-technologies-launches-sepa-instant-payments-as-a-service-on-microsoft-azure-for-r-t-1-a-nd-tips)

#### 2018
- [FIMBank deploys Volante's Payments as a Service in the cloud on Microsoft Azure](https://www.volantetech.com/news-events/press-releases/volante-technologies-launches-payments-as-a-service-on-microsoft-azure-for-fimbank)
- [VolPay PSD2 Open Banking solution released, selected by Bank Leumi (UK) and Qatar International Bank (UK)](https://www.volantetech.com/news-events/press-releases/bank-leumi-selects-volante-technologies-volpay-open-banking-psd2-solution)
- [Volante releases Designer 6.0 to accelerate API banking and cloud deployment](https://www.volantetech.com/news-events/press-releases/volante-technologies-releases-designer-version-6)

#### 2017
- First US RTP transaction Nov 2017 sent by BNY Mellon through Volante's VolPay Real-time Payments solution
- [Release of NACHA's ISO 20022 Validator, powered by Volante's cloud-based ISO 20022 translation service](https://www.volantetech.com/iso-20022-migration)
- VolPay made available in the cloud on Microsoft Azure

#### 2015
- Launch of VolPay, a suite of business applications for payments transformation and modernization across the entire payments lifecycle: corporate onboarding and initiation, hub processing, clearing gateways, and payments integration components

#### 2013
- ‘SEPA Accelerator’ launched to speed up SEPA compliance for corporates and banks

- Middle East and Africa operations expanded with office in Dubai

#### 2012
- Volante relocates from Silicon Valley to the financial hub of New York City and significantly grows its client base of top tier institutions, including:

    - Two of the highest volume stock exchanges in the US and UK
    - Two global tier 1 custodians
    - One of the world’s largest card networks
    - Europe’s largest clearing corporation
    - Three Fortune 100 corporations

#### 2001
- Volante Technologies founded in Silicon Valley with a clear purpose: to help financial institutions transcend the limitations of their archaic technology by providing modern solutions that simplify the complexity of their operations and accelerate business outcomes

### Company Results

Volante has an impressive number of metrics which demonstrate it is a market leader in terms of its client base, platform performance and success through the number of industry awards it has revceived. While these are all significant, it is important to look at the financial results as a key measure of ultimate performance and continuance. Two key metrics will be examined which is company revenue and employee count. Source data linked for each.

 - [Revenue $157 Million](https://www.zoominfo.com/c/volante-technologies-inc/125502068)
 - [Employees 750](https://www.zoominfo.com/c/volante-technologies-inc/125502068)

 It is difficult to look further into Volante's financial status to determine other key metrics like Gross\Net Profit Margin, Cash Flow, Operating Ratio, Sales Growth, Head Count ration etc. This is becuase Volante is not a publicly listed company and as such does not need to comply with particular reporting and regulation requirements in comparison to a publicly listed company. The best indicator for company results I believe can be observed through their transaction processing metrics, client base and industry awards and recognition.  

## Recommendations

I would suggest that their core business does not change they just expand their products and services.   

According one of the worlds largest professional services companies PwC - 

[***Global cashless payment volumes are set to increase by more than 80% from 2020 to 2025, from about 1tn transactions to almost 1.9tn, and to almost triple by 2030***](https://www.pwc.com/gx/en/industries/financial-services/publications/financial-services-in-2025/payments-in-2025.html)

![](https://www.pwc.com/gx/en/financial-services/fs-2025/pwc-future-of-payments-web-charts2.png)

Volante are a facilitator of such global exchanges and as such are positioned well to take advantage of further growth in this domain. What could potentially change though is the definition of what a global exchange is. 

Volante has been excellent at creating consistent entry points for a myriad of financial transaction types. I'm suggesting they add blockchain technologies and crypto currencies to their list of services. While blockchain enables distributed banking and essentially peer to peer transacting, Volante plays in the enterprise space of which there is significant regulation and reporting requirement. There is an opportunity to secure and track b2b payments using blockchain, as well as establishing a payment system that can cater for crypto currencies specifically for large regulated enterprises.

I think it would benefit Volante as it would not only expose them to future technology related to crypto currency payments and blockchain business logic but would also position them ready to utilise the technology in the future when more applications for it become available. No one can predict the future or accurately convey the impact blockchain will have on world wide payment systems and business process execution logic. I think consciously developing and looking for opportunities within the Volante Technology stack to push in these areas is key to being ready to quickly identify and move on future opportunities 

I believe investment in such technologies are appropriate as they are just the next iteration of "Payments". Volante has been able to move with the times and incorporate solutions for legacy systems like Wire\RTGS, ACH,SWIFT and realtime payments. I think its appropriate that Volante consider emerging technologies for the transfer of funds using an enterprise banking lens, which will be different from the consumer and personal lens. 

## Report Presentation
### Written by 
- **Adam Freeman** 
- **MailTo** - adam.freeman@outlook.com.au
- **GitHub** - [apfreeman](https://github.com/apfreeman)
- **Case Study File Location** - [Here](https://github.com/apfreeman/Unit-1-Homework-Assignment-FinTech-Case-Study#readme)

