Information System Development methodologies Assignments   - Travel Call Centre
===================
## Group 5
Kevin Hong 13223882   
Gyeongmin Ko  12627701  
Cheng Zhang 12717144  
Congkai Liu 13160458   
Liang Yujun 12786277  
- - - - - - - -
## Table of Contents 

<!--ts-->
- [Table of Contents](#table-of-contents)  

- [Problems and objective](#problems-and-objective)
    * [Problems](#problems)
    * [Objective](#objective)
  
- [Stakeholders](#stakeholders)

- [Design approach](#design-approach)
    * [Empathy design](#empathy-design)
    * [How Might We Statements](#how-might-we-statements)

- [Work products and Models](#work-products-and-models)
    * [Use case diagrams](#use-case-diagrams)
    * [Activity diagrams](#activity-diagrams)
    * [Class diagrams](#class-diagrams)
    * [Collaborative Diagrams](#collaborative-diagrams)

- [Competitive advantages and Risk](#competitive-advantages-and-risk)
    * [Competitive advantages](#competitive-advantages)
    * [Risk management](#risk-management)
    
- [Conclusion](#conclusion)

- [Video Presentation](#video-presentation)

- [References](#references)

<!--te-->

## Problems and objective
### Problems
The current solution of managing calls for this travel company’s call centre is unnecessarily complicated and due to having many holiday packages of different natures and type it is extremely difficult for the relationship managers (RM) to be able to provide a personalised and quality service to every customer. 

### Objective
1. Store information on relationship managers relating to their age, sex, culture, language proficiency, experience and product knowledge in “RM Profiles”
2. Use both the inbuilt RM Profiles and Profiler Tool to match relationship managers with high product knowledge to customer segments most likely to purchase that product.
3. Use ongoing information such as how effective and efficient relationship managers are in selling packages to customers and updating that in their RM Profile.
4. For outbound calls the system needs to extrapolate information from an external database to create a Profiler Tool and then match them with appropriate relationship managers based on their RM Profiles.
5. Score customers who are more likely to call back on a scale of 1-10 based on factors such as if they repeat the call and match them to appropriate relationship managers
6. Have an Interactive Voice Response to gather information from the customers when they call to build their customer profile
7. Have another interactive voice response that asks in-depth questions to reduce perceived wait times for the customer and build a more comprehensive customer profile.
8. Overall speed up the calling process to reduce lost sales due to long wait times


### Assumption 
1. The system will be easy enough to use with little training
2. The system will not be bottlenecked by hardware and will constantly be upgraded as needed
3. Employees will be the main conveyor of information about holiday packages to customers and will have a role in processing the sale 
4. There will be continued software updates and bug fixes to keep the system working as expected
5. It is assumed that with the system it will raise sales by improving how calls are allocated to relationship managers
6. It is assumed that the system can effectively process human voices gathered from the interactive voice response and change it to text that can be used to create a customer profile

## Stakeholders
![Travel call centre Stakeholder](https://github.com/khred/IDSM-Tutorial-Group-5/blob/master/Stakeholder_v2.jpg)

## Design approach
> Please write description of design approach here
<!-- toc -->

### Empathy Design

<!-- Use below HTML table format to update your Empathy map-----------

<table width="605">
	<tbody>
		<tr>
			<td colspan="2" width="1000">
				<p><strong>Empathy Map -&nbsp;Type your stakeholder here</strong></p>
				Please write "WHO are we empathizing" part from empathy map here
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Think and Feel</strong></p>
			</td>
			<td width="481">
		          <p> 
                    - point <br />
                    - point <br />
                    - point <br />
                    - point 
               	 </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>See</strong></p>
			<td width="481">
		            <p> 
                    - point <br />
                    - point <br />
                    - point <br />
                    - point 
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Say</strong></p>
			</td>
			<td width="481">
                    <p> 
                    - point <br />
                    - point <br />
                    - point <br />
                    - point 
                </p>
			</td>
		</tr>
		<tr>        
			<td width="122">
				<p><strong>Do</strong></p>
			</td>
			<td width="481">
		          <p> 
                    - point <br />
                    - point <br />
                    - point <br />
                    - point 
                </p>
			</td>
		</tr> 
        <tr>
			<td width="122">
				<p><strong>Hear</strong></p>
			<td width="481">
		          <p> 
                    - point <br />
                    - point <br />
                    - point <br />
                    - point 
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Pain</strong></p>
			<td width="481">
		          <p> 
                    - point <br />
                    - point <br />
                    - point <br />
                    - point 
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Gain</strong></p>
			<td width="481">
		          <p> 
                    - point <br />
                    - point <br />
                    - point <br />
                    - point 
                </p>
			</td>
		</tr>
	</tbody>
</table>

 -->

<!-- Gyeongmin Ko Eempathy map. -->
<table width="605">
	<tbody>
		<tr>
			<td colspan="2" width="1000">
				<p><strong>Empathy Map -&nbsp;System Testing leader</strong></p>
				Due to understaffing issues, the system testing team is not able to deliver enough system testing analyses report with various measures and advise modifications/re-verification to the information system development team.                
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Think and Feel</strong></p>
			</td>
			<td width="481">
		          <p>
                    - How can we deliver perfect system testing to ensure that we provide correct information process to the customers <br />
                    - We feel pressured due to our team didn't deliver enough feedback to the Information system Development (ISD) team.<br />
                    - We feel physically exhausted because of the understaffing on our team.  <br />
                    - How can we deliver a fast and accurate test report to the ISD team? <br />
                    - Should we develop the testing tool that helps us regarding our current project?<br />
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>See</strong></p>
			<td width="481">
		           <p> 
                    - See team members watching the computer screen all day, writing a report <br />
                    - ISD team leader talking to our team to provide them with testing report <br />
                    - Team member testing and review the system manually
                 </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Say</strong></p>
			</td>
			<td width="481">
		          <p> 
                    - Discussing the result and recommend modifications with the Project manager and ISD team <br />
                    - Speaking to the team regarding the system  <br />
                    - Talking to the interactive voice system for testing  <br />
                    - Presenting results to the ISD Team and Project manager 
                 </p>
			</td>
		</tr>
		<tr>        
			<td width="122">
				<p><strong>Do</strong></p>
			</td>
			<td width="481">
                    <p> 
                    - Creating a summary report for ISD Team and Project Manager <br />
                    - Testing the Interactive voice system  <br />
                    - Advise any recommendation/modification with ISD Team <br />
                    - Talking to the team regarding assigned tasks.
                 </p>
			</td>
		</tr> 
        	<tr>
			<td width="122">
				<p><strong>Hear</strong></p>
			<td width="481">
		          <p> 
                    - Team member's voice that testing interaction voice system <br />
                    - Team complaints regarding understaffing <br />
                    - Project manager and ISD team asking for the report  <br />
                    - Robotive Interactive voice from the phone or speaker 
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Pain</strong></p>
			<td width="481">
		          <p> 
                    - Repeat the same test process when ISD Team modifies the system regarding small or large changes<br />
                    - High individual staff workload <br />
                    - Require flexible time mangement to provide more accurate and detail feedback <br />
                    - Slowly causing damage on every team member’s vocal cords due to testing interaction voice system. <br />
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Gain</strong></p>
			<td width="481">
		          <p> 
                    - The qualified interaction voice system will provide benefits to the company  <br />
                    - Faster caller matching process  <br />
                    - Satisfy customer by providing correct information system technology to save time. <br />
                    - Improve technical knowledge regarding the interactive system and database implement system  <br />
                    - Built a better relationship with another team by providing them with high quality results. <br />
                </p>
			</td>
		</tr>
	</tbody>
</table>
    
<!-- Yujun Liang Eempathy map. -->
<table width="605">
	<tbody>
		<tr>
			<td colspan="2" width="1000">
				<p><strong>Empathy Map -&nbsp;Information system development team </strong></p>               
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Think and Feel</strong></p>
			</td>
			<td width="481">
		          <p>
                    - How can we deliver an information system to develop the operation of in-house call management centre  <br />
                    - No clue about the plan for building the new system, feel confused.<br />
                    - Considering what kind of server and development environment is suitable for the new system.  <br />
                    - Should we develop a user guide for first-time use? <br />
                                   </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>See</strong></p>
			<td width="481">
		           <p> 
                    - There is no existing information system for matching suitable RM to the specific customer, each call is assigned to a random RM,  the RM’s skill may not  match customer needs <br />
                                    </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Say</strong></p>
			</td>
			<td width="481">
		          <p> 
                    - What kind of system and function do you want to develop? <br />
                    - How do you match RM and the customer based on the infomation given <br />
                    - What User interface style do you prefer? <br />
                 </p>
			</td>
		</tr>
		<tr>        
			<td width="122">
				<p><strong>Do</strong></p>
			</td>
			<td width="481">
                    <p> 
                    - Develop a new system based on the requirements from RM and customers. <br />
                    - Modifying the new system based on the suggestion from the System test team. <br />
                    - Report the process of the new system to the project manager. <br />
                    - Debug and maintaining the system.
		    - Presenting new system to all employees. 
                </p>
			</td>
		</tr> 
        	<tr>
			<td width="122">
				<p><strong>Hear</strong></p>
			<td width="481">
		          <p> 
                    - Project manager asking to finish the new system before the deadline <br />
                    - The complaint from the customer wanting a skilled and well-matched relationship manager <br />
                    - The test result and suggestion from the system test team  <br />
                    - The complaint from the user unfamiliar with the new system  
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Pain</strong></p>
			<td width="481">
		          <p> 
                    - A large database and matching system requires a lot of resources, including space, time and server power which is hard to manage easily <br />
                    - Hard to build a customized information system without previous, existing systems to develop off. <br />
                    - Hard to meet all requirement from project manager and Test team<br />
                              </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Gain</strong></p>
			<td width="481">
		          <p> 
                    - After development, their sales increase from more effectve matching and thus the team gets paid <br />
                    - Develop their skill regarding building a customized information system <br />
                    - Satisfaction from RM a customer by providing a new information system.. <br />
                    - Through working with the other team, they gain communication skill. <br />
                </p>
			</td>
		</tr>
	</tbody>
</table>

<!-- Congkai Liu Eempathy map. -->
<table width="605">
	<tbody>
		<tr>
			<td colspan="2" width="1000">
				<p><strong>Empathy Map -&nbsp;Relationship Manager</strong></p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Think and Feel</strong></p>
			</td>
			<td width="481">
		          <p> 
                    - How to find interested customers <br />
                    - How do I please customers <br />
                    - Can I retain customers and maintain long-term cooperation <br />
                    - How to get customers to pay 
               	 </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>See</strong></p>
			<td width="481">
		            <p> 
                    - Colleagues are under pressure <br />
                    - Very little rest time <br />
                    - Competition among tourism companies <br /> 
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Say</strong></p>
			</td>
			<td width="481">
                    <p> 
                    - What kind of package do you want to know about? <br />
                    - What is your price budget <br />
		    - Where would you like to go?
		    - What would you like to do?
                    - If you are not satisfied, I can introduce other packages that may be better suited for you <br />
                </p>
			</td>
		</tr>
		<tr>        
			<td width="122">
				<p><strong>Do</strong></p>
			</td>
			<td width="481">
		          <p> 
                    - Spend more time looking for customers <br />
                    - Learn more about what customers are interested in <br />
                </p>
			</td>
		</tr> 
        <tr>
			<td width="122">
				<p><strong>Hear</strong></p>
			<td width="481">
		          <p> 
                    - Colleagues complain that they need to answer too many calls a day <br />
                    - The boss said to be attentive to for every customer and cater for their needs <br />
                    - Friends say I'm on the phone all day <br />
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Pain</strong></p>
			<td width="481">
		          <p> 
                    - Lose customer because I don't know enough about packages <br />
                    - Can't get enough commissions/bonuses <br />
                    - Fatigued every day from work<br />
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Gain</strong></p>
			<td width="481">
		          <p> 
                    - Want to have more customers <br />
                    - Establish long-term cooperation with customers <br />
                    - Each phone call does not need to waste too much time <br />
                    - Higher performance so that I can get higher commission 
                </p>
			</td>
		</tr>
	</tbody>
</table>

</table>


<table width="605">
	<tbody>
		<tr>
			<td colspan="2" width="1000">
				<p><strong>Empathy Map -&nbsp;Customer</strong></p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Think and Feel</strong></p>
			</td>
			<td width="481">
		          <p> 
                    - I want a holiday to somewhere I want at a good price <br />
                    - I want to talk to someone knowledgable about what they are talking about <br />
                    - I want a holiday package that is that will best suit my needs
		    <br />
               	 </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>See</strong></p>
			<td width="481">
		            <p> 
              - I see many different websites selling many similar holiday packages <br />
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Say</strong></p>
			</td>
			<td width="481">
                    <p> 
		    - Talking to Relationship managers about what they expect out of a holiday package <br />
                    - Talking to the automated voice and giving them information about their needs, wants and budget <br />
                    - Ask questions about the difference between holiday packages and customisation options <br />
                </p>
			</td>
		</tr>
		<tr>        
			<td width="122">
				<p><strong>Do</strong></p>
			</td>
			<td width="481">
		          <p> 
                    - The different variety of packages available from the relationship managers <br />
                    - The voice of the automated voice system <br />
                    - The voice of the relationship managers <br />
                </p>
			</td>
		</tr> 
        <tr>
			<td width="122">
				<p><strong>Hear</strong></p>
			<td width="481">
		          <p> 
                    - The different variety of packages available from the relationship managers <br />
                    - The voice of the automated voice system <br />
                    - The voice of the relationship managers <br />
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Pain</strong></p>
			<td width="481">
		          <p> 
                    - Having an overwhelming amount of information available on the internet <br />
                    - Having many different places to travel to with a wide variety of different things to do but not knowing which one would be best <br />
                    - Having many types of holiday packages for with different advantages and disadvantages and costs and being unable to know which one will be the best <br /> 
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Gain</strong></p>
			<td width="481">
		          <p> 
                    - Have someone give them a holiday destination and package that has good value and has features that customers actually want <br />
                    - Save time and money <br />
                    - Getting a better holiday than they would have gotten without the new system <br />
                    - Have less stress and peace of mind that they got the best package possible 
                </p>
			</td>
		</tr>
	</tbody>
</table>
  
            
### How Might We Statements 
**How might we**  
In the Definition stage, our team investigated the general problems that Travel Company currently has, such as
- Lack of workers to deal with future customers
- Causing un-necessary time waste for both customers and staff.
- The communication and contract system between the call centre and travel agents is not clear. 
- Even if the customer is connected to the employee or relationship manager, it is difficult to obtain accurate information.

Therefore our team came up with one clear problem statement.  
**"How might we save time while delivering accurate information to customers and grow the company stably?**

By using the "How Might We" problem statement, the team classified the main statement features into three different views to effectively address the issues within the scope. 

**Relationship Manager(Employee)**  
- How might we reduce work pressure for RM  
- How might we increase the probability of a customer successfully placing an order  
- How might we establish long-term cooperation with customers  
- How might we increase RM's enthusiasm and motivation for work  
- How might we improve the company's reputation to attract more customers  

**Travel Company CEO(Business)**
- How might we reduce work pressure for employees within a sufficient budget.   
- How might increase our profit
- How might we provide more high-quality services to Customers  
- How might we improve company value  
 
 
**Customer (Consumer)**  
- How might we deliver clearly to the relationship manager  
- How might we save our time  
- How might we use given information wisely 




## Work products and Models

We made a few important points when we approached the design and prototype. The first point was a simple process. We decided that we should skip the complicated process and deliver the most accurate and relevant information to our customers. Next point was privacy. We tried to proceed with the process without requiring personal information as much as possible. The last point was to accurately understand the needs of the customers by meeting the requirements of the points above.

We created AI voice interaction prototype system. During the AI voice interaction we simulated how customers actaully interacted with AI voices on peak time. 

### Use case diagrams
Use case diagram of the interaction between Customer and Call center employee 
![Use Case diagrams_Kevin](https://github.com/khred/IDSM-Tutorial-Group-5/blob/master/Diagrams_Folder/Use%20Case%20Diagram.jpg)

### Activity diagrams
Activity diagram explaining both in/out direction of call center system
![Activity_Call_in_Congkai](https://github.com/khred/IDSM-Tutorial-Group-5/blob/master/Diagrams_Folder/Call-in%20System.jpg)
![Activity_Call_out_Congkai](https://github.com/khred/IDSM-Tutorial-Group-5/blob/master/Diagrams_Folder/Call-Out%20System.jpg)

### Class diagrams
![Class_Diagrams_Cheng](https://github.com/khred/IDSM-Tutorial-Group-5/blob/master/Diagrams_Folder/Class.png)

### Collaborative Diagrams
![Collaborativ_Diagram_Yujun](https://github.com/khred/IDSM-Tutorial-Group-5/blob/master/Diagrams_Folder/Collaborative%20diagram.jpg)


## Competitive advantages and Risk
### Competitive advantages
The call service center system we have introduced has great competitive advantages over the original system or other systems on the market. This automation provides customers with the best matching method, effectively reducing the complexity of the company's original system and meeting the needs of different customers. Users can know more clearly what problems should be solved by whom, greatly reducing the intermediate links, which enables each service request to be transmitted to the most appropriate service representative at the most appropriate time and in the most appropriate way, greatly optimizing the service process of tourism enterprises. Let tourists save more time and trust the services of our travel agencies. Similarly, our point-to-point service will avoid unnecessary labor waste and greatly reduce the operating cost of the company. It is the most important operation policy of our system to be able to provide value-added services for enterprises, improve service quality and reduce enterprise operation costs.

### Risk management
<table style="border: none;border-collapse:collapse;">
    <tbody>
        <tr>
            <td style="border-width: 1pt;border-style: solid;border-color: black black windowtext;border-image: initial;padding: 3pt;height: 18pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:12px;font-family:"Times New Roman",serif;color:black;background:white;'>Financial Requirement</span></strong></p>
            </td>
            <td style="border-top: 1pt solid black;border-right: 1pt solid black;border-bottom: 1pt solid black;border-image: initial;border-left: none;padding: 3pt;height: 18pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:12px;font-family:"Times New Roman",serif;color:black;background:white;'>First Month</span></strong></p>
            </td>
            <td style="border-top: 1pt solid black;border-right: 1pt solid black;border-bottom: 1pt solid black;border-image: initial;border-left: none;padding: 3pt;height: 18pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:12px;font-family:"Times New Roman",serif;color:black;background:white;'>Second Month</span></strong></p>
            </td>
            <td style="border-top: 1pt solid black;border-right: 1pt solid black;border-bottom: 1pt solid black;border-image: initial;border-left: none;padding: 3pt;height: 18pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:12px;font-family:"Times New Roman",serif;color:black;background:white;'>Third Month</span></strong></p>
            </td>
            <td style="border-top: 1pt solid black;border-right: 1pt solid black;border-bottom: 1pt solid black;border-image: initial;border-left: none;padding: 3pt;height: 18pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>Cost</span></strong></p>
            </td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid black;border-bottom: 1pt solid black;border-left: 1pt solid black;border-image: initial;border-top: none;padding: 3pt;height: 24pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>ISD team</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 24pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$14000.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 24pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$14000.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 24pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$14000.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 24pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$42,000.00</span></p>
            </td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid black;border-bottom: 1pt solid black;border-left: 1pt solid black;border-image: initial;border-top: none;padding: 3pt;height: 24pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>Test team</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 24pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$6000.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 24pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$6000.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 24pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$6000.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 24pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$2400.00</span></p>
            </td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid black;border-bottom: 1pt solid black;border-left: 1pt solid black;border-image: initial;border-top: none;padding: 3pt;height: 24pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>Software device, office supplies</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 24pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$2000.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 24pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:justify;font-size:14px;font-family:DengXian;margin-right:24.0pt;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$2000.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 24pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:justify;font-size:14px;font-family:DengXian;margin-right:15.0pt;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$2000.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 24pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$6,000.00</span></p>
            </td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid black;border-bottom: 1pt solid black;border-left: 1pt solid black;border-image: initial;border-top: none;padding: 3pt;height: 15pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>Equipment Repair</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 15pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$1000.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 15pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$1000.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 15pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$1000.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 15pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$3,000.00</span></p>
            </td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid black;border-bottom: 1pt solid black;border-left: 1pt solid black;border-image: initial;border-top: none;padding: 3pt;height: 15pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>Internet</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 15pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$120.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 15pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$120.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 15pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$120.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 15pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$360.00</span></p>
            </td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid black;border-bottom: 1pt solid black;border-left: 1pt solid black;border-image: initial;border-top: none;padding: 3pt;height: 33pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>Server, Hardware device IT infrastructure cost</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 33pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:right;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>/</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 33pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:right;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>/</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 33pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$4000.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 33pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$4,000.00</span></p>
            </td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid black;border-bottom: 1pt solid black;border-left: 1pt solid black;border-image: initial;border-top: none;padding: 3pt;height: 15pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>Maintain</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 15pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:right;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>/</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 15pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:right;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>/</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 15pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$3000.00</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 15pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$3,000.00</span></p>
            </td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid black;border-bottom: 1pt solid black;border-left: 1pt solid black;border-image: initial;border-top: none;padding: 3pt;height: 17pt;vertical-align: top;"><br></td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 17pt;vertical-align: top;"><br></td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 17pt;vertical-align: top;"><br></td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 17pt;vertical-align: top;"><br></td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 17pt;vertical-align: top;"><br></td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid black;border-bottom: 1pt solid black;border-left: 1pt solid black;border-image: initial;border-top: none;padding: 3pt;height: 17pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><strong><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>TOTAL</span></strong></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 17pt;vertical-align: top;"><br></td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 17pt;vertical-align: top;"><br></td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 17pt;vertical-align: top;"><br></td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid black;border-right: 1pt solid black;padding: 3pt;height: 17pt;vertical-align: top;">
                <p style="margin:0cm;margin-bottom:.0001pt;text-align:left;font-size:14px;font-family:DengXian;"><span style='font-size:10px;font-family:"Times New Roman",serif;color:black;background:white;'>$60760.00</span></p>
            </td>
        </tr>
    </tbody>
</table>

**Risk management and possible effects if the project fails**  
**Risk factor:**  
Technologies:
1.	The new system may not be compatible with the legacy call system.
2.	The Overloading issue caused by idle users and peak time calling.
3.	Long-term system maintenance.

Security issue:
1.	System hacking and unauthorized access.
2.	Downtime issue.
3.	Private user data protection issues 
4.	Damage to the system by staff misuse.

Customer/RM
1.	Unfamiliar with the UI and system functionalities.
2.	User guide and frequently asked question constant renew among with the new system

**Possible effects if the project fails**  
If the development project fails, the major impact will be time invested and capital spent. At the current stage, The entire project plan costs $60,760.00, the waste of capital may cause financial difficulties to the company, the capital spent can be used in other parts of the business like advertising. Consumed time is also another impact, including requirement gathering, scrum development, analysis, and the design of the prototype, to complete the above phases requires at least 3 months which may be wasted.


## Conclusion
The above is the improvement plan proposed by our group for the call center system of the travel company. Our improvement plan solves a series of problems such as the complexity of the company's package and low-quality customer service. We use a relatively simple development method to provide personalized and quality services for each customer, increasing the sales volume and reputation of the travel company. In the development process, we used the Scrum method for iterative development. Experience the advantages and disadvantages of Scrum development. Also, through this project, we learned how to use Github and some new code, which increases our knowledge of the IT field. At the same time, we also believe that there is still room for improvement in this program improvement, and we look forward to more in-depth exploration next time.

## Video Presentation

Please click below link to access Youtube Video of our group's presentation.  
https://www.youtube.com/watch?v=KrkECVOK8HE&t=1s


## References
David, B. 2016, Agile Coaching Tip: What is an Empathy Map, viewed 24 August 2020, < https://www.solutionsiq.com/resource/blog-post/what-is-an-empathy-map/>.

Jennifer, B. 2018, Empathy Mapping: A Guide to Getting Inside a User’s viewed 24 August 2020, < https://www.uxbooth.com/articles/empathy-mapping-a-guide-to-getting-inside-a-users-head/>.

Kahootz 2019,How to create an effective stakeholder engagement stratege, viewed 20 May 2020,<https://www.kahootz.com/how-to-create-an-effective-stakeholder-engagement-strategy/

Kevin, M. 2019, UML Collaboration Diagrams viewed 27 May 2020, 
< https://www.codemag.com/Article/0205051/UML-Collaboration-Diagrams>.

Lucidchart 2018, UML Use Case Diagram, 26 May 2020, 
< https://www.lucidchart.com/pages/uml-use-case-diagram>.

Lucidchart 2018, UML Class Diagram Tutorial, viewed 26 May 2020, 
< https://www.lucidchart.com/pages/uml-class-diagram >.

MindTools, Empathy Mapping, Understanding Targeted, viewed 24 May 2020, 
< https://www.mindtools.com/pages/article/empathy-mapping.htm>
