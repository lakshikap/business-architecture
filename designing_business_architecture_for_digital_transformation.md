<h1 align="center"> Designing Business Architecture for Digital Transformation Initiatives </center></h1>
<p align="center">
<i>
Version: April 2021<br/>
</i>
</p>

**_Original Author_**

+ Lakshika Paiva | Associate Lead Business Analyst - [WSO2, Inc](https://wso2.com/) | [@lakshikapaiva](https://twitter.com/lakshikapaiva)


## 1.0 Introduction

Enterprises are constantly facing many challenges due to the changing nature of the internal and external business environments. Subsequently, a small resulting change in the business can impact multiple processes, cost of systems and practices, even without adding any value to an enterprise but disrupting the operational areas that were even working well.

As a result, organizations have turned to digital transformation as a strategic solution to be enabled to respond to shifts in trends, customer behaviors and business needs.

Business Architecture primarily focuses on aligning an enterprise&#39;s strategy execution with the business strategy on a people, process and technology front and eventually forming a bridge with the enterprise architecture. However, there&#39;s ample evidence of enterprises which have failed to align their digital transformation to their business needs. Although business architecture plays a vital role in this aspect, there is very little indication to say that it is being used in an optimal manner. There are many architecture frameworks, industry bodies [1] in and researchers that have put forward different ideas and definitions to business architecture. These are arising from the increasing awareness of the need to hold a formal definition of the architecture of their business. However, they do not provide a guideline or approach to designing business architecture with applications from industry practice.

This paper aims to provide clarity and guidance to bridge this gap in the business architecture discipline. It is based on knowledge gathered from the cross-cutting disciplines of business strategy, value creation, information systems strategy and business architecture concepts, as well as continuous analysis of enterprises and practice in the industry. It also embodies a logical approach to aligning strategy with execution.

The paper is organized into five main sections:

+ Presents the representative components of a business architecture
+ Basic guide to designing business architecture
+ Illustrates a real-world scenario of a Postal Service and applies the guideline in practice
+ Discusses the iterative development of business architecture in agile environments
+ Return on investment: evaluating the returns and benefits

## 1.0 Business Architecture and its Main Components of Representation

Business Architecture is an abstract depiction of the strategic alignment of an enterprise&#39;s execution strategy to the business strategy. The former is represented by the information technology strategy and organization strategy (refer figure 1). It can also be simplified as people, processes and technology.


<p align="center">
  <img src="https://github.com/lakshikap/business-architecture/blob/ea1d8e010a155c53c8143759da098ba3f5f2b6e4/images/BA%20in%20Strategy.png">
</p>
<p align="center">

   
<p align="center">
<i>
Figure 1: Role of Business Architecture in Strategy
</i>
</p>

Source: [Strategic Alignment Article](https://lakshikapaiva.medium.com/business-architecture-and-the-strategic-enterprise-9f5b5ade485)
   

**Key characteristics of business architecture are:**

- Represents the scope of the business
  - It spans the process, function, business unit or entire company as required by the initiative.
- Abstract in nature
  - It is important to note that business architecture is designed at a strategic level hence the business capabilities, values and other components are depicted in an abstract manner. It translates strategy for execution.
- Reusable across the business
  - As the enterprise grows, this also evolves. Business units may have their own business architectures designed when they transformed, and rather than designing dependencies from scratch, they can be cross-referenced and reused to reduce overhead.
- Developed iteratively
  - Digital transformation initiatives are a journey and not a destination. It is a continuous initiative to achieve and maintain sustainable competitive advantage for digital enterprises. This demands agility and flexibility built into the digital way of life. Business architecture enables this digital way of life through its iterative nature, and it is in fact a living artifact.

Designing a business architecture in an abstract manner requires identification of the different components that represent it. The most basic components are explained in table 1 below.


  
**Table 1:** Main components of business architecture representation

<p align="center">
  <img src="https://github.com/lakshikap/business-architecture/blob/ea1d8e010a155c53c8143759da098ba3f5f2b6e4/images/Table%201.png">
</p>

<p align="center">

The next section presents a step-by-step approach to designing a business architecture using these components.

## 2.0 Guide to Designing a Business Architecture

Once the above components are well-interpreted, designing a business architecture can follow the following steps:

- Identify the key business objectives that impact the digital transformation initiative,
- Identify the current business capabilities of the area that the initiative impacts,
- Analyze issues and identify gaps to achieve business objectives, along with stakeholders.
- Identify the new or revamped business capabilities that are desired by the digital transformation,
- Identify the customer-oriented value flows among business capabilities and how they contribute to the overall transformation,

With these steps in mind, the next section presents a real-world scenario and explains the approach to designing its futuristic business architecture. In the practical initiative, the digital transformation of this European Governmental Postal Service was carried out using API and integration technology.

## 3.0  Digital Transformation of a Country-wide Postal Service

A Postal Service in Europe is looking forward to transforming their services with regards to handling parcels and letters for their country. The high-level operation is illustrated in figure 2 below.


<p align="center">
  <img src="https://github.com/lakshikap/business-architecture/blob/ea1d8e010a155c53c8143759da098ba3f5f2b6e4/images/Postal%20Service%20-%20Business.png">
</p>

<p align="center">
  
  <p align="center">
<i>
Figure 2: Current business conduct of the Postal Service
</i>
</p>


They have their own staff who sort incoming parcels and letters, categorize them based on the state or area that they need to be sent to, and then send them to the distribution centers in the locality for last-mile delivery (refer figure 2). The service operation is currently handled partially manually and involves a few existing systems which are legacy and with limited functionality.

The Leadership has identified a number of inefficiencies in the way parcels and letters was handled in the entire country and wanted to transform how they operate. The parcels and letters delivery industry has transformed over the years to provide better services to customers, however at a higher cost. Customers were benefitting, but those who were using the national service were facing consequences of a now cumbersome postal service, countrywide. Internally, there was an elephant in the room. There were a lot of manual operations, the current systems were legacy and had become cumbersome, and customers were demanding for better services. The costs of daily operations had increased with the addition of new services that were not designed optimally. The team set out to solve this problem by analyzing these issues deeper and defining what they wanted to achieve strategically (refer to this[blog](https://blog.architect2architect.com/strategic-alignment-of-digital-transformation-initiatives-5af637e98a9d) for more details on defining strategic objectives, performance indicators and results).

Let&#39;s follow the steps defined in section 3.0 above.

**Step 1:** Identifying the key objectives of the enterprise that have a direct impact on the digital transformation initiative.

Key strategic objectives of the Postal Service are:

1. **Reduce business cost:** Lower operating costs of the postal service operations
2. **Operational excellence:** Improve efficiency of operations
3. **Improve customer experience:** Increase customer value through digital services

In addition, the Postal Service wants to explore the opportunity to expose data and services (via APIs) to external app developers to develop innovative digital services that offer value-added services. These resulting digital services can be monetized to generate revenue for the postal service as well. However, public services are usually not revenue-driven, hence we do not elaborate on this aspect further as a deliberate business objective. It is important to note that these objectives are business-focused needs and not necessarily defined in a technology-oriented manner. Further, at the end of this initiative, the postal service aspires to achieve the following positioning and competitive advantage in the market:

<i>
"To be the value-added service provider for parcels and letters delivery in the country by offering superior, yet affordable services to customers."
</i>

Ideally, the strategic objectives are derived as a result of an internal and external strategic analysis of the postal service environment. However, this paper does not include in its scope the elaborate process of strategic analysis, strategy formulation and strategy implementation (refer figure 3 and this [article](https://blog.architect2architect.com/strategic-alignment-of-digital-transformation-initiatives-5af637e98a9d) for more information). Instead, it directly dives into the problem analysis to provide an understanding of the internal environment and its key issues that led to this digital transformation initiative. As such, the ideal derivative process can be shown in figure 3 below.


<p align="center">
  <img src="https://github.com/lakshikap/business-architecture/blob/ea1d8e010a155c53c8143759da098ba3f5f2b6e4/images/Strategy%20Process.png">
</p>

<p align="center">
  <p align="center">
<i>
Figure 3: Process of Strategy
</i>
</p>


However, it is acknowledged that the process in this article takes a reverse order for the purpose of better explanation.

**Step 2:** Identifying the current business capabilities and processes concerned with the digital transformation initiative.

Following are the existing business capabilities. Note that they are abstract, significant business activities and add value to the customer in the end, i.e., deliver parcels and letters to the customer.

- Parcel and letter receipt
- Parcel and letter, sorting and categorizing
- Address identification
- Route plan creation
- Parcel and letter delivery
- Customer call center services

**Step 3:** Analyzing issues and identifying gaps to achieving business objectives, along with stakeholders.

In a thorough internal analysis of the postal service, following problems were identified.

1. **Time -consuming process:** When a customer brings in a parcel or letter, it needs to be sorted by addresses to collate all parcels and letters going through to each area and postcode. This process is time consuming as staff has to read the address on the parcels and letters and put it into the relevant bag/bin.
2. **Human errors:** The addresses are read manually by staff, and this adds to the process times and also opens up room for error. Sometimes, letters can be sent to wrong locations if they are not sorted accurately.
3. **Inaccuracy of data:** Customers&#39; handwriting is difficult to read, which adds to the above issue as well. Often this leads to letters being delivered to the wrong neighborhood.
4. **Inefficient routing:** The delivery team of drivers are given a manually (partial) prepared route every day. This is a cumbersome activity as it involves multiple factors to be considered for optimal routing - like locations, routes, traffic, human concerns and weather conditions to meet the set SLA for on-time delivery.
5. **Lack of information and business insights:** Customers often call the call center to check on the progress of their parcels and letters delivery. This is an added cost for the center as more calls means more effort going into catering to these growing requests. In response, the call center also has very limited information of the location of delivery fleet, individual customer parcels and letters progress etc.
6. **Increasing customer complaints:** Customers complain about waiting times at the post office, poor visibility into parcels and letters delivery progress etc. Customer numbers are dwindling, and satisfaction rates are low.
7. **Increasing costs:** Costs are centered on manual labor and maintenance of Parcel and letter storage in postal service locations in provinces. Also, last-mile delivery costs incurred due to poor routing plans resulting in additional fuel consumption, traffic, location identification and waiting times due to customer delays on accepting registered letters.

The above issues are classified against the corresponding business capability and its related objective have been stated in the table 2 below.

**Table 2:** Alignment of business capabilities to objectives

| **Existing business capability** | **User** | **Issues/ gaps** | **Business Objective** | **Initiative Objectives** |
| --- | --- | --- | --- | --- |
| Parcel and letter receipt | CustomerStaff | Customer interface point – time spent on providing details on parcels and letters, sender and hand-over. Hand-written addresses are difficult to read. | Customer experience.Operational excellence. Reduce business cost. | Provide a self-service online portal or kiosk at post-office.Enable optical character recognition (OCR) mechanism to capture address. Create and print the barcode on the envelope/ parcels and letters.Read address to determine the postage and ability to rectify if incorrect. |
| Parcel and letter, sorting and categorizing | Staff | Time consuming process where addresses have to be read and categorized by province and postcode. Room for human error. | Operational excellence. Reduce business cost | Automate the parcels and letters packaging and sorting using the above mechanism. |
| Address identification | Staff | Hand-written addresses can be interpreted inaccurately.Room for human error. As a result, letters can be sent to wrong locations. | Operational excellence and improve customer experience. | Automate address identification process through OCR as above. |
| Route plan creation | Staff | Schedules are created every day and sent to 20,000 delivery personnel (including postman or postwoman). Inefficient process. Lack of information in a central location to create an optimal schedule of delivery. | Achieve operational excellence. | Automate the route plan and schedule creation process. |
| Parcel and letter delivery (last mile) | Driver | Manual process to send/ receive location updates to/ from drivers and infrequent. Inefficient schedule leads to higher fuel consumption. | Operational excellence and customer experience. | Provide mechanisms to send location updates and notifications via mobile. |
| Customer call center services | Call center staff | No accurate information on delivery progress and frustrated customers. Sometimes parcels and letters are delivered late or to wrong locations. Low quality of information available for informed business decision-making. Time spent at customer interface point. | Reduce business cost.Operational excellence.Improve customer experience. | Enable OCR data capture and auto-validation mechanism to ensure accuracy. Capture metrics to increase visibility into business. |

**Step 4:** Identify the new or revamped business capabilities that are desired by the digital transformation.

Based on the issues and gaps identified in table 2, new business capabilities were identified in alignment with the strategic objectives (Refer table 3). These were derived with careful consideration in order to introduce capabilities that offer competitive advantage in the industry.

**Table 3:** New and improved capabilities

| **#** | **Business capability** | **Justification** | **Type** | **Critical Success Factors (CSF)** | **KPIs** |
| --- | --- | --- | --- | --- | --- |
| 1 | Printed address labels - self-service label creation | Customers can provide information online, print the label for the parcels and letters at home and avoid waiting times at the post office. | New | Reduce waiting times. Accurate information capture and processing. | Time spent in the queue/ customer.Affordability per customer. |
| 2 | Parcel or letter scanning - Address reading and barcode tagging | The addresses are read and labelled electronically, and a barcode is generated for tracking purposes. | New and improved | Reduce labor cost. Employee efficiency and productivity. | Number of parcels and letters processed per day. |
| 3 | Parcel or letter sorting – electronic sorting | Based on scanned information, parcels and letters are sorted into different locations. | Improved | Efficiency of internal operations. Reduce time and labor cost. | Number of errors in sorting.Efficiency and productivity (%). |
| 4 | parcels and letters tracking and updates | Barcode scanner on the driver&#39;s mobile is used to scan and share the live location of the parcels and letters to staff and customers. | New | Improve visibility and accuracy of delivery information. | Frequency of updates on live location and accuracy (%). |
| 5 | Optimal route planning and navigation | An automated mechanism to design the schedule in an optimal manner considering routes, traffic, weather etc. | Improved | Faster schedule creation. Predictable delivery times. Reduce delivery costs. | Time taken to create a schedule.Cost of fuel per Parcel/ letter.Speed of delivery per Parcel/ letter. |
| 6 | Business dashboards | A central dashboard that collates all information from business activities and presents trends and reports for strategic decisions. | New | Business intelligence. Visibility into operations, better decision-making. | Productivity andEfficiency (%).Visibility of information - e.g., cost of operations. |
| 7 | Call center services | Employees have an organized approach to work, more information captured and usable during call center services, more information captured for decisions. | Improved | Customer experience, operational excellence | Customer satisfaction rate (NPS score).Employee productivity (%). Number of complaints per day. |
| 8 | Digital services ecosystem | Creating more avenues for generating revenue by exposing specific information and allowing app developers to build new digital services. | New | Customer experience, variety of value-added services, | Ecosystem revenue amount, Increase in user growth due to value-added services. |

**Step 5:** Identify the customer-oriented value flows among business capabilities and how they contribute to the overall transformation.

The key value flows are identified in association with each business capability. Along with this step, the desired business architecture can be represented as shown in figure 4 below. It is important to note that the value flow shown in blue arrows do not present the flow of operations, but the value flowing from each business capability that adds to the overall business architecture.

<p align="center">
  <img src="https://github.com/lakshikap/business-architecture/blob/ea1d8e010a155c53c8143759da098ba3f5f2b6e4/images/Postal%20Service%20-%20Desired%20Biz-Arc.png">
</p>

<p align="center">
  
<p align="center">
<i>
Figure 4: Desired Business Architecture
</i>
</p>


The identified business objectives are depicted on the top of the diagram, with a brief guide on the left side of figure 4. Compare figure 2 and 4 for a better understanding of how the business capabilities have changed and improved.

While the business architecture depicts the strategic perspective, it does not show quantifiable information from key performance indicators, although they are important for proposing an improved perspective for the digital transformation initiative. Hence, an evaluation framework is proposed below.

## 4.0 Iterative Development of Business Architecture in Agile Environments

Digital transformation is a journey and often enterprises adopt Agile practices in these initiatives to ensure products are developed iteratively. Unfortunately, most companies adopt the waterfall-agile process instead of the ‘true’ agile practice. Following diagram (refer figure 5) depicts how business architecture develops hand-in-hand with a true agile implementation. The objective is to illustrate how business architecture supports the true agile practice by smooth integration.

<p align="center">
  <img src="https://github.com/lakshikap/business-architecture/blob/5a2f96a46e0edba8290a485bd4fe64c99cafffb8/images/BA%20in%20agile%20process%20-%20Agile%20chart.png">
</p>

<p align="center">
  
<p align="center">
<i>
Figure 5: Business architecture & support for 'true' agility
</i>
</p>

In an agile environment, the minimum viable product (MVP) is the first deliverable. For the first sprint, a few customer journeys are analyzed to identify the relevant user stories that are suitable to form the MVP. In this process, one or two customer journeys can be selected for which the user stories are derived. Simultaneously, the business architect can identify the business capabilities, while developers build the first milestone. 

In the context of the Postal Service scenario, the strategy is already known by the time the initiative is kicked-off. There are two main customer scenarios captured in the scope of this story, which can be broken down into several other variations:

+ The letter posting process 
  + Normal letter
  + Registered letter
  + Local or international letters
+ The parcel sending process
  + Local or international parcels
  + Parcels by priority


The posting of a normal local letter can be considered as the main customer journey for the MVP as it is the most common occurrence in the Postal Service. Thereafter, in the analysis of the current process, existing business capabilities and values can be captured in the first sprint. While deriving the requirements, the new capabilities and new values can be identified and incorporated into the business architecture in subsequent sprints, thereby improving the business architecture iteratively as the development progresses. 


## 5.0 Return on Investment

**Framework for Evaluating Achievement**

Once the formal digital transformation initiative has completed major phases or agile sprints with significant outcomes, they can be compared with the business architecture. There are two perspectives to this:

- The main objective of the business architecture is to provide [strategic alignment of the execution to the objectives and strategy](https://blog.architect2architect.com/strategic-alignment-of-digital-transformation-initiatives-5af637e98a9d) of the company.

This is achieved on a daily basis through business outcomes such as by reducing the cost of operations, improving customer&#39;s experience with the Parcel or letter and packaging service through visibility into the progress of the delivery etc. In that sense, the strategic and long-term business outcomes of the initiative are achieved through the defined CSF and KPIs in table 3 which can be evaluated on an ongoing basis. They tie into the objectives set out in step 1 discussed in this approach and in turn, contribute to achieve the desired competitive advantage in the long-term - &quot;_To be the value-added service provider for parcel and letter delivery in the country by offering superior, yet affordable services to customers.&quot;_

- However, on a more initiative-focused approach, the KPIs in table 2 can be used to measure the before and after states of the achievements. These are more short-term and are achieved instantly during the course of the initiative, and not suitable for assessing the strategic alignment.

**Benefits of Business Architecture**

There are a number of advantages of designing and maintaining a business architecture for an enterprise. 
+ First and foremost, it enables an enterprise to maintain strategic alignment and achieve the vision, objectives and corporate or business strategy. While the vision is farfetched, the objectives provide a more quantifiable approach to achieving the vision. This has been explained in the section ‘Framework for Evaluating Achievement’.
+ Promoting organizational health and well-being by generating an ability to be flexible and agile in the delivery, enabled by its iterative nature.
+ Responding to changes or exploiting opportunities arising from the external and internal environment, as beneficial to the enterprise and in turn to create a favourable outcome. 
+ Facilitating enterprise performance and growth in a competitive marketplace by implementing best practices, encouraging reuse and monitoring metrics to deliver value to customers. 

## Summary

In consclusion, this paper presents a simple, but pragmatic approach to designing business architecture for digital transformation initiatives in alignment with an enterprise's strategic objectives. It discusses a five-step approach to designing business architecture from the identification of its individual components and the organization of these components in one illustration. This is presented by applying the 5-step model to a real-world Postal Service in Europe. The business architecture goes hand in hand with the solution architecture of the initiative and is part of the enterprise architecture. The iterative nature of the business architecture makes it a suitable candidate for the popular agile approach to implementation in digital initiatives. Once the initiative has produced significant outcomes, they can be compared using the two-pronged evaluation framework presented in this paper. Overall, business architecture is a perfect candidate for business professionals or leadership teams to realize the value of digital transformation.

**Bibliography**

- Gordon Barnett, Gene Leganza, &amp; Audrey Hecht. (2020). _Business Architecture In 2025 And Beyond_ [Analyst Report]. Forrester.[https://bit.ly/2QYGw2V](https://bit.ly/2QYGw2V)
- Marcus Blosch &amp; Saul Brand. (2019). _Toolkit: Construct Business Architecture Deliverables That Deliver Value to Business Leaders_. Gartner Inc.[https://gtnr.it/3fCywz5](https://gtnr.it/3fCywz5)
- Johnson, G., Whittington, R., &amp; Scholes, K. (2011). _Exploring Corporate Strategy_ (9th edition). Pearson.
- Whelan, J., &amp; Meaden, G. (2016). _Business Architecture: A Practical Guide_ (1st edition). Routledge.
- Yeates, D., Cadle, J., Eva, M., Hindle, K., Paul, D., Rollason, C., &amp; Turner, P. (2014). _Business Analysis_ (3rd edition). BCS, The Chartered Institute for IT.

**Footnotes:**
[1]Some such bodies are TOGAF, Business Architecture Guild and The Open Group, while others include analysts like Forrester and Gartner etc.
