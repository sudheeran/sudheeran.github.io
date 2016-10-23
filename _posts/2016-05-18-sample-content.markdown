---
layout: default
title:  "Everything a product manager needs to know about analytics!"
date:   2016-05-18 14:50:00
categories: main
---

<h2><span>Everything a product manager needs to know about analytics - by Simon Cast</span></h2>

<figure><img src="/images/Analytics.jpg" title="RankBrain"></figure>

Everyone knows analytics are important for product managers. But, like lots of things everyone knows, not everyone knows why they are important and in the case of analytics even necessarily what they are. This post is going to look at:

<ul>
	<li>What exactly are analytics?</li>
	<li>Concepts of analytics</li>
	<li>implementing analytics</li>
	<li>Measuring analytics</li>
	<li>Reporting analytics</li>
	<li>Analytics and experimentation</li>
</ul>


<h3><span>What exactly are analytics?</span></h3>

Put simply, analytics measure the state of the product, what users are doing, what they are clicking on, etc. These measurements tell us what is going on with the product, although not necessarily why this is going on. A measurement by itself tells you very little and is not analytics. It is only when a series of measurements are collected together that they become analytics.

To illustrate the difference, consider this example. The temperature of an object is a measurement, but only becomes analytics once you include things like the position, velocity, composition, temperature of the environment, etc. Combined with these other measurements the temperature of the object can now tell you what is happening to the object. Let’s say the velocity is 0, the position is 1 metre off the ground and the temperature of the surroundings is the same. We can now say that the object is stationary, 1 metre off the ground at the same temperature as the surroundings.

The more independent measurements you have the better you can characterise the state of the system or how people are using your product.

Why are analytics important?

Analytics are important for one major reason: What you don’t measure, you can’t improve.

Without knowing what the state of the system is, it is very hard, if not impossible, to do much to change or affect the system. You can, of course, make changes  blind, but without analytics you will never know whether the system was changed or whether nothing happened. It allows you to see what is currently happening, make a change and see what effect the change has.

Analytics only tells you what is going on and not why it is going on. Without analytics it is down to random chance whether your product will succeed or fail.


<h3>Analytics Concepts</h3>

Within analytics there are a key set of concepts that need to be understood in order to derive the best value from both analytics and metrics. These concepts are focused on interpretation of the data so that you can gain insight.

The four concepts are : Data points, Segmentation, Funnels, Cohorts


<h3>Implementing Analytics</h3>

The default behaviour when implementing analytics seems to be to throw in an analytics packages and hope you’ve got the bases covered.


The process of planning consists of these steps:

<ul>
	<li>Define the product vision</li>
	<li>Define the KPIs that meet the product vision</li>
	<li>Define the metrics that allow you to hit your KPIs</li>
	<li>Define the funnels (via user journeys) that affect your metrics</li>
</ul>

With that you can work out what data points you need to collect to allow you to calculate the metrics and produce the funnels. The plan is not static and you’ll need to revisit the plan regularly to update it based on changes to KPIs, product maturity and changing vision.

<h3>Measuring Analytics</h3>

Now that a plan detailing what needs to be measured and collected exists, the next task is determining how to measure and collect the data. There are two primary ways to do this, either in-house or externally.

In-house is building a measurement system into the system. In-house systems can be tailored to the specific measurement needs and analysis desired. The drawback is the need to maintain both the collection and analysis side of it. In effect in-house becomes another system that has to be built and maintained, consuming valuable resources.

External are third-party-provided systems that measure the system and provide access to the measured data. Examples are Google Analytics (GA), Mixpanel and KISSmetrics. External measurement platforms remove the need to build and maintain a new product and tend to be very quick to implement (often the inclusion of a JS file and some tagging). However, they aren’t always able to measure what you might need and can be difficult to tailor to meet customised analysis needs.

<h3>Reporting Analytics</h3>

If you don’t report on the analytics, even to yourself, then it is a waste of time implementing them. Use them or loose them. The trick with reporting is to do it in a manner that is easily grasped by everyone in the company. What you want to achieve from the report is less ‘x happened’ than prompting everyone to ask: “Why did x happen? Why did it change?” By answering or attempting to answer these questions the system can be tuned to improve it.

The two common methods for reporting are comparison and trends. The comparison shows how a metric has changed between two points in time. Say for example this week and last next. The trend is shown by the change in a metric over a period of time. For example, a chart showing a metric for each day over the past month.

<h3>Analytics And Experimentation</h3>

Analytics and experimentation are intertwined. Analytics answers “what is going on with x?” and experimentation tests “how do we improve x?”. The analytics measures the KPIs and resulting changes from experiments that then proves or dispproves the hypothesis the experiment was setup to test.

<h3>Summary</h3>

Analytics are critical as they tell you what is going on in your product. Before launching and implementing a platform to measure data, plan what needs to be measured. This forms the criteria for choosing how to measure the data, whether to use an in-house system, external service or a combination of both. Finally, use reporting to help stimulate your team to ask “why is it that happening?”


Source : <a style="font-size:14px; color: #1e6bb8;" href="http://www.mindtheproduct.com/2013/02/everything-a-product-manager-needs-to-know-about-analytics/" target="_blank">Read Full Article</a>