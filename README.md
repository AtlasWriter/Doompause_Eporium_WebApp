<!DOCTYPE html>
<html lang="en">
<head>
</head>
<body>
<div class="container">
  <div class="Logo">
    <img src="https://assets.codepen.io/10811741/Doompause_Emporium_Logo_Edit.png" alt="" />
  </div>
  <div class="Assignment-members-and-details" style="background-color:Tomato;">
    <h1>Doompause Emporium - Ecommerce WebApp with Strip Payment Processing</h1>

<h2>Final Design Report:</h2>

<p>This application was written as an assignment from Grand Canyon University as a Student Collaboration<strong>&nbsp;CST-326 10/22/2023</strong>. This document will address is the&nbsp;development of a web application for online sales. The company, with its rich history in the trade of medieval weapons, is seeking to expand its reach to customers globally through an online platform. Background Information:&nbsp;The company has been in business for hundreds of years, offering medieval weapons for both defensive and offensive combat. Over the years, it has built a reputation for quality and authenticity. However, with changing times and the rise of digital commerce, the company has found it increasingly difficult to reach customers.The proposed web application will allow users to view items, read weapon descriptions, and see the prices of the items. It will also offer an online shopping cart where customers can add, remove, and edit the quantity of products. This digital transformation aims to make shopping more convenient for customers and expand the company&rsquo;s customer base.By addressing these needs, the company hopes to continue its tradition of excellence while adapting to the modern marketplace.</p>

<p>AUTHORS-</p>

<p>&nbsp;&nbsp;&nbsp;</p>

<table cellspacing="0" class="Table" style="border-collapse:collapse; border:none; margin-left:7px; width:630px">
	<tbody>
		<tr>
			<td style="background-color:#d9d9d9; border-bottom:1px solid black; border-left:1px solid black; border-right:1px solid black; border-top:1px solid black; vertical-align:top; width:186px">
			<p>Name</p>
			</td>
			<td style="background-color:#d9d9d9; border-bottom:1px solid black; border-left:none; border-right:1px solid black; border-top:1px solid black; vertical-align:top; width:240px">
			<p>Role</p>
			</td>
			<td style="background-color:#d9d9d9; border-bottom:1px solid black; border-left:none; border-right:1px solid black; border-top:1px solid black; vertical-align:top; width:204px">
			<p>Department</p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid black; border-left:1px solid black; border-right:1px solid black; border-top:none; vertical-align:top; width:186px">
			<p>Daniel Rumfelt</p>
			</td>
			<td style="border-bottom:1px solid black; border-left:none; border-right:1px solid black; border-top:none; vertical-align:top; width:240px">
			<p>Backend, Security, Angular, Payment Processin</p>
			</td>
			<td style="border-bottom:1px solid black; border-left:none; border-right:1px solid black; border-top:none; vertical-align:top; width:204px">
			<p>Software Engineering</p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid black; border-left:1px solid black; border-right:1px solid black; border-top:none; vertical-align:top; width:186px">
			<p>Christa Moncrief</p>
			</td>
			<td style="border-bottom:1px solid black; border-left:none; border-right:1px solid black; border-top:none; vertical-align:top; width:240px">
			<p>Frontend, GUI and Database Development</p>
			</td>
			<td style="border-bottom:1px solid black; border-left:none; border-right:1px solid black; border-top:none; vertical-align:top; width:204px">
			<p>Web Design, GUI</p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid black; border-left:1px solid black; border-right:1px solid black; border-top:none; vertical-align:top; width:186px">
			<p>Ryan Coon</p>
			</td>
			<td style="border-bottom:1px solid black; border-left:none; border-right:1px solid black; border-top:none; vertical-align:top; width:240px">
			<p>Backend, FrontEnd and Database Development</p>
			</td>
			<td style="border-bottom:1px solid black; border-left:none; border-right:1px solid black; border-top:none; vertical-align:top; width:204px">
			<p>Software Engineering</p>
			</td>
		</tr>
	</tbody>
</table>
<h2>Key Technical Design Decisions :</h2>

<table border="0" cellpadding="1" cellspacing="1" style="width:674.6px">
	<tbody>
		<tr>
			<td style="width:106px">
			<p>&nbsp;<img alt="interactive connection" src="https://cdn.freebiesupply.com/logos/large/2x/angular-icon-1-logo-png-transparent.png" style="float:left; width:35px" />&nbsp;Angular</p>
			</td>
			<td style="width:99px">
			<p><img alt="html cleaner" src="https://getbootstrap.com/docs/5.2/assets/brand/bootstrap-logo-shadow.png" style="float:left; width:45px" />Boostrap</p>
			</td>
			<td style="width:98px">
			<p><img alt="Word to html" src="https://www.logolynx.com/images/logolynx/98/980c5fe716efb66c936eebe1937d5489.png" style="float:left; width:45px" /> Spring Boot</p>
			</td>
			<td style="width:92px">
			<p><img alt="replace text" src="https://th.bing.com/th/id/OIP.D87KXcDLtggvLLrmHnairwHaJG?pid=ImgDet&amp;rs=1" style="float:left; width:35px" />&nbsp; &nbsp;Spring Security</p>
			</td>
			<td style="width:124px">
			<p><img alt="gibberish" src="https://th.bing.com/th/id/OIP.Wd9moNdvBsgsNDMl6V1BegHaCn?pid=ImgDet&amp;rs=1" style="float:left; width:45px" />&nbsp;REST API</p>
			</td>
			<td style="width:125px">
			<p><img alt="html table div" src="https://th.bing.com/th/id/R.255b77e251b19a6d0600634d2ff9b006?rik=2D3kq1fky6LYpg&amp;pid=ImgRaw&amp;r=0" style="float:left; width:45px" />&nbsp;Database</p>
			</td>
		</tr>
	</tbody>
</table>

<h2>Risks:</h2>

<p>Assumptions, risks, and constraints are an integral part of the technical design process. Here are some that could affect the technical design of the system:</p>

<p style="margin-left:40px"><em><strong>Assumed Factors:</strong></em></p>

<ol>
	<li>Reliable Third-Party Services: It&rsquo;s assumed that third-party services such as the payment gateway are reliable and secure.</li>
	<li>Stable Internet Connection: The system assumes users have a stable internet connection for seamless browsing and transactions.</li>
	<li>User Tech Savviness: It&rsquo;s assumed that users have a basic understanding of how to navigate web applications.</li>
</ol>

<p style="margin-left:40px"><em><strong>Identified Risks:</strong></em></p>

<ol>
	<li>Third-Party Service Failure: There&rsquo;s a risk that third-party services might experience downtime or other issues, affecting the application&rsquo;s functionality.</li>
	<li>Security Breaches: Despite using secure payment gateways, there&rsquo;s always a risk of security breaches and data theft.</li>
	<li>Technical Debt: Rapid development to meet deadlines might lead to shortcuts and workarounds, accumulating technical debt.</li>
</ol>

<p style="margin-left:40px"><em><strong>Constraints:</strong></em></p>

<ol>
	<li>Budget: The budget could limit the number of features that can be implemented or the technologies that can be used.</li>
	<li>Time: The project timeline might not allow for extensive testing or the implementation of all desired features.</li>
</ol>

<p style="margin-left:40px"><em><strong>Potential Solutions:</strong></em></p>

<ol>
	<li>Backup Third-Party Services: Have backup third-party services in case the primary ones fail.</li>
	<li>Regular Security Audits: Conduct regular security audits to identify and fix potential security vulnerabilities.</li>
	<li>Prioritize Features: Prioritize features based on their impact on user experience and business value to manage time and budget constraints effectively.</li>
</ol>

<p>The actual factors will depend on the specific circumstances of the project and should be identified through thorough analysis and discussion with all stakeholders.</p>

<h2>Technical Requirements:</h2>

<table border="1" cellpadding="1" cellspacing="1" style="width:846.6px">
	<thead>
		<tr>
			<th scope="col" style="width: 53px;">FR ID</th>
			<th scope="col" style="width: 66px;">TI ID</th>
			<th scope="col" style="width: 712px;"><strong><span style="font-size:11.0pt"><span style="font-family:&quot;Times New Roman&quot;,serif">Technical Requirement</span></span></strong></th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td style="width:53px">&nbsp;</td>
			<td style="width:66px">001</td>
			<td style="width:712px"><span style="font-size:12.0pt"><span style="font-family:&quot;Times New Roman&quot;,serif">Lombok to reduce boiler plate code. Lombok.jar - Backend</span></span></td>
		</tr>
		<tr>
			<td style="width:53px">&nbsp;</td>
			<td style="width:66px">002</td>
			<td style="width:712px"><span style="font-size:12.0pt"><span style="font-family:&quot;Times New Roman&quot;,serif">Upgrade to Java Development Kit 21</span></span></td>
		</tr>
		<tr>
			<td style="width:53px">&nbsp;</td>
			<td style="width:66px">003</td>
			<td style="width:712px">
			<p><span style="font-size:12.0pt"><span style="font-family:&quot;Times New Roman&quot;,serif">import jakarta.persistence.Entity;&nbsp; import jakarta.persistence.Table;&nbsp; import java.math.BigDecimal; import java.util.Date;</span></span></p>
			</td>
		</tr>
		<tr>
			<td style="width:53px">&nbsp;</td>
			<td style="width:66px">004</td>
			<td style="width:712px"><span style="font-size:12.0pt"><span style="font-family:&quot;Times New Roman&quot;,serif">Custom REST Resource: @RepositoryRestResource(collectionResourceRel = &quot;productCategory&quot;, path = &quot;product-category&quot;) in DAO product category interface. Name of JSON entry path is the /product-category.</span></span></td>
		</tr>
		<tr>
			<td style="width:53px">&nbsp;</td>
			<td style="width:66px">005</td>
			<td style="width:712px"><span style="font-size:12.0pt"><span style="font-family:&quot;Times New Roman&quot;,serif">MySQL57Dialect has been deprecated; use org.hibernate.dialect.MySQLDialect instead</span></span></td>
		</tr>
      		<tr>
			<td style="width:53px">&nbsp;</td>
			<td style="width:66px">006</td>
			<td style="width:712px"><span style="font-size:12.0pt"><span style="font-family:&quot;Times New Roman&quot;,serif">Springboot 4, JpaRepositorys, JDBC Driver, WebDev Tools, Crud Repository.</span></span></td>
		</tr>
	</tbody>
</table>

</body>
</html>
