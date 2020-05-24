Information System Development methodologies Assignments   - Travel Call Centre
===================
## Group 5
Kevin Hong Red 13223882   
Gyeongmin Ko  12627701  
Cheng Zhang xxxxxxxx  
Congkai Liu xxxxxxxx   
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

- [References](#references)

- [Appendices](#appendices)

<!--te-->

## Problems and objective
### Problems
The current solution of managing calls for this travel company’s call centre is unnecessarily complicated and due to having many holiday packages of different nature and type it is extremely difficult for the relationship managers (RM) to be able to provide a personalised and quality service to every customer. 

### Objective
1. Store information on relationship managers relating to their age, sex, culture, language proficiency, experience and product knowlege in “RM Profiles”
2. Use both the inbuilt RM Profiles and Profiler Tool to match relationship managers with high product knowledge to customer segments most likely to purchase that product.
3. Use ongoing information such as how effective and efficient relationship managers are in selling packages to customers and updating that in their RM Profile.
4. For outbound calls the system needs to extrapolate information from an external database to create a Profiler Tool and then match them with appropriate relationship managers based on their RM Profiles.
5. Score customers who are more likely to call back on a scale of 1-10 based on factors such as if they repeat call and match them to appropriate relationship managers
6. Have a Interactive Voice Response to gather information from the customers when they call to build their customer profile
7. Have another interactive voice response during periods of high calls that asks more in depth questions to reduce perceived wait times for the customer and build a more comprehensive customer profile.
8. Overall speed up the calling process to reduce lost sales due to long wait times


### Assumption 
1. The system will be easy enough to use with little training
2. The system will not be bottlenecked by hardware and will constantly be upgraded as needed
3. Employees will be the main conveyor of information about holiday packages to customers and will be have a role in processing the sale 
4.There will be continued software updates and bug fixes to keep the system working as expected
5. It is assumed that with the system it will raise sales by improving how calls are allocated to relationship managers
6. It is assumed that the system is able to process human voices gathered from the interactive voice response and change it to text that can be used to create a customer profile

## Stakeholders
![Travel call centre Stakeholder](https://github.com/khred/IDSM-Tutorial-Group-5/blob/master/Stakeholder_v2.jpg)

## Design approach
> Please write description of design approach here
<!-- toc -->

### Empathy Design

<!-- Use below HTML table fomat to update your Empathy map-----------

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
				Due to the understaffed issue, system testing team is not able to deliver enough system testing analyses report with various measures and advise modifications/re-verification to the information system development team.                
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Think and Feel</strong></p>
			</td>
			<td width="481">
		          <p>
                    - how can we deliver perfect system testing to ensure to provide correct information process to the customers <br />
                    - Feel pressured due to our team did not deliver enough feedback to the Information system Development (ISD) team.<br />
                    - Feeling physically exhausted because of the understaffed on our team.  <br />
                    - How can we deliver fast and accurate test report to the ISD team? <br />
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
                    - Talking to the interaction novice system for testing  <br />
                    - Presenting result to the ISD Team and Project manager 
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
                    - Testing on the Interaction voice system  <br />
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
                    - Team complain regarding understaffed <br />
                    - Project manager and ISD team asking for the report  <br />
                    - Mechanical Interaction voice from the phone or speaker 
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Pain</strong></p>
			<td width="481">
		          <p> 
                    - Repeat the same test process when ISD Team modifies the system regarding small or large changes<br />
                    - Need to recruit more staff to reduce the workload <br />
                    - Require flexible time mangement to provide more accurate and detail feedback <br />
                    - Slowly cussing damage on every team member’s vocal cords due to testing interaction voice system. <br />
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
                    - Improve technical knowledge regarding the interaction system and database implement system  <br />
                    - Built a better relationship with another team by providing them with the quality result. <br />
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
                    - No clue with the plan for building the new system, feel confused.<br />
                    - Considering what kind of server and developing environment is suitable for the new system.  <br />
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
                    - How do you match RM and the customer( the criteria)?<br />
                    - What User interface style you preferred?<br />
                    - Presenting new system to all employees. 
                 </p>
			</td>
		</tr>
		<tr>        
			<td width="122">
				<p><strong>Do</strong></p>
			</td>
			<td width="481">
                    <p> 
                    - Develop a new system based on the requirement from RM and Customer. <br />
                    - modifying the new system based on the suggestion from the System test team. <br />
                    - Report the process of the new system to the project manager. <br />
                    - Debug and maintaining the system.
                 </p>
			</td>
		</tr> 
        	<tr>
			<td width="122">
				<p><strong>Hear</strong></p>
			<td width="481">
		          <p> 
                    - Project manager asking finish the new system before the deadline <br />
                    - The complaint from the customer regarding they want a skilled and well-matched customer <br />
                    - The test result and suggestion from the system test team.ort  <br />
                    - The complaint from the user unfamiliar with the new system  
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Pain</strong></p>
			<td width="481">
		          <p> 
                    - A large database and matching system requires a lot of resources, including space, server and time consuming(coding) <br />
                    - Hard to build a customized information system without previous, existing examples. <br />
                    - Hard to meet all requirement from project manager and Test team<br />
                              </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Gain</strong></p>
			<td width="481">
		          <p> 
                    - After development, their holiday packages sales benefit from the new system, sales increased, they got the pay  <br />
                    - Develop their skill regarding building a  customized information system <br />
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
                    - What kind of package do you want to know <br />
                    - What is your price budget <br />
                    - If you are not satisfied, I can introduce other content for you <br />
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
                    - The boss said to be supreme for every customer <br />
                    - Friends say I'm listening to the phone all day <br />
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Pain</strong></p>
			<td width="481">
		          <p> 
                    - Lose customer <br />
                    - Can't get a generous salary <br />
                    - Work fatigue every day <br />
                    - Be thoughtful when talking to customers 
                </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>Gain</strong></p>
			<td width="481">
		          <p> 
                    - want to have more customers <br />
                    - stablish long-term cooperation with customers <br />
                    - Each phone call does not need to waste too much time <br />
                    - Higher performance，Get more commission 
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
				Please write "WHO are we empathizing" part from empathy map here
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
                    - point 
               	 </p>
			</td>
		</tr>
		<tr>
			<td width="122">
				<p><strong>See</strong></p>
			<td width="481">
		            <p> 
                    - I see many different websites selling many similar holiday packages <br />
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
                    - Call the travel agency to get information about what's available <br />
                    - Book holiday packages <br />
                    -  <br />
                    - 
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

 -->    
            
### How Might We Statements 
**Realtionship Manager**

- How might we reduce work pressure for RM
- How might we increase the probability of a customer successfully placing an order
- How might we establish long-term cooperation with customers
- How might we increase RM's enthusiasm and motivation for work
- How might we improve the company's reputation in order to attract more customers



## Work products and Models
> Please shot work products 
<!-- toc -->

### Use case diagrams
> Please inseart use case diagrams here

### Activity diagrams
> Please inseart Activity diagrams here

### Class diagrams
> Please inseart Class diagrams here

### Collaborative Diagrams
> Please inseart collaborative disgrams here


## Competitive advantages and Risk
### Competitive advantages
> Please write potential benefits to the call centre(in terms of reducing cost and being able to carry out more effective calls)

### Risk management
> Please write possible effects if the project fails



## Conclusion
> Please write conclusion here


## References
> Please put references here



## Appendices
> Please put appendics here

