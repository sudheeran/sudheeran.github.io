---
layout: default
title:  "How to write a Product Requirement Document"
date:   2016-10-10 12:50:00
categories: main
---

<h2><span>How to write a Product Requirement Document - Shoieb Yunus</span></h2>


<figure><img src="/images/prd.png" title="PRD"></figure>

<hr>

<h3><span>Example PRD : Online Garment Tracking and Management System</span></h3>

<h4>Software Requirements Specification (Sample)</h4>

<h4>Version: 0.1</h4>


<h3>1. Purpose </h3>

The purpose is to demonstrate the general understanding of an online garment tracking and management system. The web portal leverages order fulfillment and logistics practices.  


<h3>2. Scope </h3>

The scope of this document is limited to a high-level overview of the key components, functionality and steps requiring garment life cycle management module.


<h3>3. Key Components </h3>

The system consists of the following key components that need to be designed, developed and integrated for a uniform experience:

<ul>
	<li>E-Commerce platform</li>
	<li>Inventory Management and Order Fulfillment</li>
	<li>Payment System</li>
	<li>Recommendation System – Collaborative Filtering</li>
	<li>CRM (tightly coupled with Real-time Reporting and RecSys)</li>
</ul>


<h3>4. Product Requirements </h3>

<h4>4.1  Functionality</h4>

<ul>
	<li>Web site visit – user lands on the home page</li>
	<li>Display – user is shown the latest arrival of  garments</li>
	<li>User registration – user registers to browse the garment</li>
	<li>Search – user is allowed to perform search based on brands prior to capturing user profile (preferences/taste/etc.)</li>
	<li>User profile – user creates her profile for better search results</li>
	<li>Browse – user can browse the site</li>
	<li>Search – user performs search on the garment(s) based on multiple search criteria such as, garment type, size, brand, latest arrival, etc.

	<ul>
		<li>Check availability</li>
		<li>If yes, goes into the shopping cart</li>
		<li>Else, continue browsing</li>
	</ul>

	</li>
	<li>Pricing and Plan Options – user selects the pricing and plan option and enters the credit card info</li>
	<li>Credit card info is instantly verified</li>
	<li>Upon checking out, the credit card is processed</li>
	<li>Order acknowledgement email is sent to the user</li>
	<li>Order is sent to the Fulfillment Center for immediate processing</li>
	<li>Operations, Sales and Marketing are notified of the user action via CRM for relevant actions</li>
	<li>Order processing, shipping, tracking and delivery managed by the Fulfillment Center</li>
	<li>Full cycle repeats when the user sends in the garment for replacement (the Netflix model)</li>
</ul>	

<h4>4.2  Garment Life Cycle Management</h4>

The purpose of this system is to determine life of each garment based on historical/product usage data, and manage garment life cycle. Fulfillment center clerk/operator is trained to enter the required data into the system every step of the way.

<ul>
	<li>Garment visual inspection</li>
	<li>Re-kitting if missing minor parts</li>
	<li>Garment washing/steaming, folding and bagging</li>
	<li>Ready for order fulfillment</li>
	<li>Track each garments wear and tear upon each return. </li>
	<li>Determine ROI(Return On Investment) per garment and SKU (Stock Keeping Unit)</li>
	<li>When garment reaches EOL(End-of-life), then discard or auction (at a discounted rate)</li>
</ul>

<h4>4.3  GUI</h4>

<ul>
	<li>Uniform look and feel on all web pages</li>
	<li>Easy to navigate product catalog</li>
	<li>Community-building features to foster word-of-mouth and growth </li>
	<li>Product recommendations</li>
</ul>

<h3>5. Challenges</h3>

<ul>
	<li># of SKUs and total inventory management</li>
	<li>Efficiency and reliability in product delivery to the customer</li>
	<li>Data mining for decision making</li>
	<li>Timely demand fulfillment</li>
</ul>

<h3>6. Optimization</h3>

<ul>
	<li>Pull, pack and ship the same day</li>
	<li>Optimization of inventory, delivery time, resources (labor), and territory coverage</li>
	<li>As an example, what SKU’s to be stocked at which warehouse?</li>
	<li>Data capture and analysis at all times. Dashboard views for real-time data for different groups</li>
	<li>Use of predictive analytics for SKU management and cost control</li>
	<li>Features development for Users community building for early adaptors</li>
	<li>Features development for customer life cycle management from user acquisition, engagement, retention, referral and revenue</li>
</ul>


Reference : <a href="https://shoieb.quora.com/How-to-write-a-Product-Requirement-Document-PRD-101-sample" target="_blank">Shoieb Yunus</a> and <a href="https://goberoi.com/on-writing-product-specs-5ca697b992fd#.exaacfsuf" target="_blank">Gaurav Oberoi</a>