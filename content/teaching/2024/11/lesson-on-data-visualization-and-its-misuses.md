---
title: "Lesson on Data Visualization and its Misuses"
date: 2024-11-12T01:05:28
slug: "lesson-on-data-visualization-and-its-misuses"
categories: ["teaching"]
tags: ["argumentation", "Bar Chart", "Censorship", "communication", "data", "data visualization", "Ethics", "framing", "Gantt Chart", "journalism", "Line Graph", "manipulation", "methodology", "misinformation", "Misleading Visuals", "Network Analysis", "Network Graph", "Pie Chart", "research", "research method", "rhetoric", "Scaling Distortions", "SCOM 2710", "SCOM 3050", "signs", "teaching", "Timeline", "Truncated Axis", "visual rhetoric", "visualization", "War photography"]
wp_id: 833
section: teaching
---

<h4><b>Posted by Keren Wang, FA 2024</b></h4><hr/>
<h6><b>In this session, we aim to achieve several key learning objectives:</b></h6>
<ul>
<li aria-checked="false" aria-level="1"><b>Understand the fundamental principles of framing and visual rhetoric,</b> exploring how they shape the design and interpretation of data visualizations.</li>
<li aria-checked="false" aria-level="1"><b>Examine the art of designing and manipulating graphic systems of signs</b> that disclose or conceal specific quantitative or qualitative information.</li>
<li aria-checked="false" aria-level="1"><b>Identify common types of data visualizations,</b> such as bar charts, pie charts, line graphs, and network graphs, along with their appropriate applications.</li>
<li aria-checked="false" aria-level="1"><b>Recognize the advantages and potential misuses of data visualizations,</b> including manipulative techniques like framing and scaling distortions.</li>
<li aria-checked="false" aria-level="1"><b>Critically analyze real and hypothetical examples</b> to detect misleading or biased visual representations.</li>
<li aria-checked="false" aria-level="1"><b>Develop best practices for creating clear, honest, and effective data visualizations,</b> ensuring accuracy and ethical integrity.</li>
</ul>
<hr/>
<h2><b>Photography and Visual Rhetoric</b></h2>

To truly grasp the fundamental principles and perils of data visualization, we must journey back to the birth of photography and photojournalism. When photography was first employed in news reporting, it carried an inherent demand for credibility. Unlike paintings or sketches, photographs were perceived as unfiltered, unmediated representations of reality. Ironically, as our discussion will reveal, even from its inception, <a href="https://en.wikipedia.org/wiki/Photograph_manipulation">photojournalism was subject to rhetorical manipulation</a>.

The manipulation of visual information is exemplified by two notable early instances of war photography: Roger Fenton's <b><i>The Valley of the Shadow of Death</i></b> (1855) and Timothy H. O'Sullivan's <b><i>Home of a Rebel Sharpshooter, Gettysburg </i></b>(1863).

In "The Valley of the Shadow of Death," taken on April 23, 1855 during the Crimean War, Fenton captured a desolate battlefield landscape strewn with cannonballs, as seen in the version on the left:

<iframe height="480" src="https://drive.google.com/file/d/1BnZ9hYtGHOcjhWWOV9km5KNcMIh_Hhss/preview" width="640"></iframe>

Controversy arose when another version of the photograph surfaced, as seen in the version on the right: one with cannonballs scattered across the road and another with the road largely clear.  [<a href="https://www.artic.edu/artworks/123407/the-valley-of-the-shadow-of-death">1</a>] This discrepancy led to debates about whether Fenton had arranged the cannonballs to create a more dramatic scene, highlighting the potential for photographers to alter battlefield imagery to influence public perception.

Similarly, O'Sullivan's<b><i> Home of a Rebel Sharpshooter, Gettysburg</i></b> (1863) depicts a fallen Confederate soldier positioned in a rocky enclave known as “Devil's Den.” The carefully arranged placement of the rifle and the soldier's posture evoke the idealized visual composition of a Renaissance painting:

<iframe height="480" src="https://drive.google.com/file/d/1Bka7jo_IJKTD6sjAiaj55vzrJXBEgDI8/preview" width="640"></iframe>

Subsequent analysis revealed that the body had been moved approximately 40 yards from its original location, and the rifle was placed beside it to enhance the composition. This staging underscores the ethical dilemmas faced by early war photographers, who sometimes manipulated scenes to convey a particular narrative or emotional impact. [<a href="https://www.artic.edu/artworks/196395/home-of-a-rebel-sharpshooter-gettysburg">2</a>]

From its inception, photographs intended to document reality were often <a href="https://en.wikipedia.org/wiki/File:Ulysses_S._Grant_at_City_Point.jpg">doctored</a>, <a href="https://en.wikipedia.org/wiki/Valley_of_the_Shadow_of_Death_(Roger_Fenton)">staged</a>, or<a href="https://en.wikipedia.org/wiki/Kerry%E2%80%93Fonda_2004_election_photo_controversy"> framed</a> to distort information and evoke<a href="https://www.moma.org/collection/works/86695"> specific emotional reactions</a>. This reveals an essential truth: <b>photographic visualization has always been more rhetorical than purely representational</b>, subjected to the same, if not more subtle, forms of manipulation as speech and writing.

<h3><b>Visual Framing</b></h3>

Framing can  influence how a target audience interprets and responds to a message, by strategically emphasizing certain visual or textual elements while downplaying or obscuring others. [<a href="https://doi.org/10.1080/23796529.2011.11674684">3</a>] This technique can evoke different emotional reactions, guide opinions, or alter the perceived significance of an issue, ultimately steering the audience’s response in a desired direction. [<a href="https://doi.org/10.1109/TVCG.2011.255">4</a>]

A notable example of visual framing is the incident involving India's state-run Press Information Bureau (PIB) during the 2015 Chennai floods. The<a href="https://www.bbc.com/news/world-asia-india-34991822"> PIB released a photograph of Prime Minister Narendra Modi surveying the flood-affected areas</a> from an aircraft window. However, the image was later revealed to be doctored, with a separate flood scene digitally inserted into the window to enhance the visual impact:

<iframe height="480" src="https://drive.google.com/file/d/1Cj8C7GOJdHW9JQVoegaTDqBojrtFhkDQ/preview" width="640"></iframe>

Similarly, data visualizations, which we often consider objective graphical representations of facts, operate under the same rhetorical principles. Like statistics, they can be strategically crafted to shape audience perception and elicit intended reactions. Whether through framing, selective emphasis, or visual distortions, data visualizations share the same capacity for manipulation as photographic narratives. [<a href="https://doi.org/10.1109/TPC.2007.914869">5</a>] With this context in mind, let’s explore how these principles manifest across various types of visualizations, from timelines to bar charts and beyond, and uncover the rhetorical craft that underpins their design.

<hr/>
<h2><b>Timeline</b></h2>

A <b>timeline</b> is a visual representation of events arranged in chronological order. Unlike bar or line graphs, which typically focus on numeric data, timelines visualize the sequence of events. They help viewers understand the temporal relations between events and how they unfold over time.

Timelines can be oriented either horizontally or vertically. Events are plotted along a <b>time axis </b>and spaced according to when they occurred, and major milestones or periods can be highlighted with markers or annotations.

For instance, a timeline could illustrate the evolution of major classical philosophical figures from ancient China during the "Hundred Schools of Thought" period as seen in this example. By including select figures from ancient Greece and Rome on the opposite side of the time axis, the timeline provides a dual perspective, helping to contextualize these key figures within a broader historical framework.

<iframe height="480" src="https://drive.google.com/file/d/1BsnvJhcwM3Cw4n3i5LVmQVA4Vt-yqQpl/preview" width="640"></iframe>

Timelines are particularly useful for highlighting historical events or developments, such as the progression of a major war or the evolution of technological advancements.

<b>Gantt chart </b>is a specialized timeline used to show the sequence and duration of tasks in a project. One of the main advantages of Gantt charts is that they help organize and visualize complex sequences of events. Here is a more complex Gantt chart that breaks down the survey study into detailed subtasks for each major phase. This provides a clearer picture of the workflow, helping to manage and track each specific step in the process:

<iframe height="480" src="https://drive.google.com/file/d/1D44oKzdQDSN6-nzXCoc_XJHDcwoS-1yb/preview" width="640"></iframe>
<h3><b>Misuse of Timeline - Incorrect Scaling:</b></h3>

A timeline with <b>incorrect scaling</b> occurs when events are spaced unevenly or inaccurately relative to their chronological distances. See  the example below:

<iframe height="480" src="https://drive.google.com/file/d/1Bu62Vm13wIFm75oDzSp79srHkuYElzvB/preview" width="640"></iframe>

In the timeline above, events that are 5,435 years apart (between the invention of 'Writing Systems' and 'Electromechanical &amp; Digital' information technology) appear visually similar to the much greater span between 'Writing Systems' and the advent of 'Oral, Representational, and Semaphoric' systems over 100,000 years ago.

This can mislead viewers into thinking that events are either closer together or farther apart than they actually are. The inaccurate spacing may result in misinterpretations of historical progression or cause-and-effect relationships.

<b>How to Fix It: </b>Ensure equal time intervals (e.g., years or decades) are represented by equal physical spacing on the timeline:

<iframe height="480" src="https://drive.google.com/file/d/1BuA4DjRXFQ7gSe92NPei6Z4gkm3IvUx4/preview" width="640"></iframe>

In this corrected timeline with<b> consistent time intervals</b> and <b>proportional scale</b>, events that are 100,000 years apart should be visually twenty times as far apart as events that are 5,000 years apart.  If uneven spacing is unavoidable for readability, explicitly note the time differences between events.

<hr/>
<h2><b>Bar Chart</b></h2>

A <b>bar chart</b> or <b>bar graph</b> represents data with rectangular bars, where the length or height of each bar corresponds to the data value it represents. Bars can be plotted vertically or horizontally.

Each bar represents a specific category or group, with its length or height indicating the magnitude of the corresponding value. The bars are separated by spaces to emphasize that the data is discrete, rather than continuous.

Bar charts are commonly used to <b>compare quantities across different categories</b>, such as student enrollment figures for various majors. For example, if we want to compare the number of students enrolled in different majors at a university, a bar chart can present the enrollment figures for each major side by side, clearly showing which major is the most popular:

<iframe height="480" src="https://drive.google.com/file/d/1CZMyf7JSxKtJb3SHdHteK28S7LSIthBp/preview" width="640"></iframe>

Bar graphs are particularly effective for <b>highlighting differences</b>, making it easy to identify the highest or lowest values at a glance. Bar charts are simple to construct and interpret, providing a quick visual comparison. They also have the advantage of being able to display both positive and negative values.

A <b>grouped or clustered bar graph</b> such as the one shown below compares two or more groups (sub-categories) within each category. They are commonly used for comparing data across different categories and sub-categories, such as generational differences in communication preferences:

<iframe height="480" src="https://drive.google.com/file/d/1C_-VQgqe7P3odg47T23HN_QC1AFzxDOP/preview" width="640"></iframe>

A grouped bar graph is particularly effective for illustrating relationships between two categorical variables, offering a clear visual representation of complex data sets. However, they can become visually cluttered if too many groups or sub-categories are included, which may render a bar graph into a “cluster-mess.”

A<b> stacked bar graph </b>is similar to a grouped bar graph but stacks sub-category values within a single bar. This format is particularly useful for showing the proportion of sub-categories within each category while also allowing for comparisons of total values across categories, as seen in this example:

<iframe height="480" src="https://drive.google.com/file/d/1CmpaoF-mvKU6M2MPPdO1FrMxGqAUpcD9/preview" width="640"></iframe>

One advantage of a stacked bar graph is that it combines total and part-to-whole analysis, providing a comprehensive view of both the overall category size and its internal composition. Additionally, it saves space compared to a grouped bar graph, making it a more compact visualization option.

However, stacked bar graphs can make it difficult to compare individual sub-category values across different bars. They may also become visually discombobulating  when too many sub-categories are included, potentially hindering clear interpretation: <a href="https://upload.wikimedia.org/wikipedia/commons/c/cb/Union-europea_segun_rem-koolhaas.svg"><i>behold, the rainbow bar-code!</i></a>
<h3><b>Misuse of Truncated Bar Chart</b></h3>

Let’s take a look at this bar chart where the y-axis starts at a value higher than 0, exaggerating differences between categories:

<iframe height="480" src="https://drive.google.com/file/d/1CLvVGS7jRXtZ60zHkmea-MWFdKCRNR4l/preview" width="640"></iframe>

The chart exaggerates the differences between the bars by truncating the y-axis. The actual differences are small, but they appear much larger because the baseline isn’t at zero.

<b>How to Fix It: </b>Let's correct the bar chart by starting the y-axis at zero. Ensure the y-axis starts at zero to provide an accurate visual representation of the differences:

<iframe height="480" src="https://drive.google.com/file/d/1CP5-LFkxERHzlLkSeL31qeo8k5zvuBRr/preview" width="640"></iframe>

The y-axis now starts at zero. It might be less “visually dramatic,” but it provides an accurate visual representation of the differences between categories.

<hr/>
<h2><b>Pie Chart</b></h2>

Pie charts are commonly used to visualize proportions or percentages of various subcategories within a whole. For example, the <b>simple pie chart</b> below illustrates the distribution of responses to a survey on communication preferences:

<iframe height="480" src="https://drive.google.com/file/d/1CtMe_QMlWKlDk-MFI4KhU6PSM89i8N4t/preview" width="640"></iframe>

An <b>exploded pie chart</b> is similar to a simple pie chart, but one or more slices are separated from the rest to draw attention. This format is particularly useful for highlighting specific categories or outliers, such as emphasizing the most-used communication method in a survey:

<iframe height="480" src="https://drive.google.com/file/d/1CvJOFE0Uf-JCTNb_V5lHRgsYlE9E7rpZ/preview" width="640"></iframe>

A <b>doughnut chart</b> is another common variety of pie chart, distinguished by its hollow center. It serves a similar purpose to a pie chart but provides additional space in the center, which can be used for labels or other relevant information:

<iframe height="480" src="https://drive.google.com/file/d/1Cy3uKElLd_cnZRLzK6r969cX9NWynQmj/preview" width="640"></iframe>
<h3><b>Misuse of Pie Chart - Incorrectly Labeled Percentages
</b></h3>

Here is a misleading pie chart where the slice proportions do not accurately match the labeled percentages:

<iframe height="480" src="https://drive.google.com/file/d/1Cmw9kkABUxybERVQYnJLND4H9YPvs2zy/preview" width="640"></iframe>

In this example, only the 10% slice looks roughly proportional, all remaining slices are either too large or small for their stated percentage. This can mislead viewers to faulty conclusions about the data distribution.

<hr/>
<h2><b>Line Chart</b></h2>

A <b>line graph</b> or<b> line chart</b> or uses points connected by lines to represent data that changes over time or along a continuous variable.

Typically, the horizontal<b> x-axis </b>represents time or a sequential category, while the vertical <b>y-axis</b> represents the variable being measured, such as temperature, sales, or stock prices. <b>Data points</b> are plotted at the intersection of their corresponding x and y values and are then connected by lines to illustrate the changes.

Line graphs are commonly used to visualize<b> trends over time</b>, such as stock prices, daily temperatures, or monthly sales. They help identify patterns, including increases, decreases, or cyclical behavior. One of their key advantages is their ability to show how a variable changes over time, making it easier to detect trends, fluctuations, or periods of stability. Additionally, multiple lines can be plotted on the same graph to compare trends across different variables.

For example, this chart shows the income share of the richest 1% of the population in various countries from 1980 to 2014, measured before taxes and benefits. This line graph provides a clear visual representation of how income inequality has evolved across different nations over time. Each line represents a country, illustrating trends in the proportion of income received by the top 1%:

<iframe height="480" src="https://drive.google.com/file/d/1Cyi5D2vMEMnBi2fMAZLjTnXtgn8g5z1l/preview" width="640"></iframe>
<h3><b>Misuse of Line Chart - Exaggerated Slope</b></h3>

Let’s plot a graph with a y-axis that starts close to the minimum value, exaggerating the slope of the line:

<iframe height="480" src="https://drive.google.com/file/d/1CSwoHt2P5rEXi2oCSRXSUDLigKocAFwJ/preview" width="640"></iframe>

Notice that in this graph, the y-axis starts at 440, close to the minimum value of the data. This artificially steepens the slope of the line, making the increase in crime rates appear more dramatic than it actually is. The manipulation may lead viewers to believe that crime rates have risen sharply, which is not true.

Now, let’s plot the same data with a properly scaled y-axis:

<iframe height="480" src="https://drive.google.com/file/d/1CXfQ0Quz54e7l7COxPNhK7_rxFhPZWtx/preview" width="640"></iframe>

In this version, the y-axis now starts at 0, providing a more accurate representation of the actual change in crime rates over time. The gradual increase in crime rates is evident, but it does not appear as steep or alarming as in the misleading graph.

<hr/>
<h2><b>Network Graph</b></h2>
<b>Network graphs </b>are visual representations of relationships between entities (nodes) and their interactions or relations (edges). In communication research, network graphs are used to analyze various phenomena, such as social networks, communication flow, and influence patterns.

Network graphs consist of several fundamental elements. <b>Nodes</b> represent entities, such as individuals or organizations. <b>Edges</b> represent the connections or interactions between these nodes, such as communication frequency or social ties. The<b> size or color of nodes</b> is often used to indicate additional variables, such as the importance or influence of an entity, for example, the number of followers in a social network. Similarly, the <b>weight or thickness of edges</b> represents the strength or frequency of interactions, providing a visual cue about the intensity or significance of the connections.

Network graphs are widely applied in several areas. One key application is <b>Social Network Analysis (SNA)</b>, which involves studying the structure of social relationships, such as the connections between individuals within a community. Another common use is in <b>Communication Flow</b>, where network graphs help visualize how information moves within an organization or across various platforms. Additionally, they are employed in <b>Influence and Interaction Analysis</b>, which focuses on identifying key influencers or hubs within communication networks, such as prominent social media influencers.

Here is a network graph representing hypothetical user interactions across three major anonymous discussion boards: <a href="https://en.wikipedia.org/wiki/2channel">2channel</a>, <a href="https://en.wikipedia.org/wiki/4chan">4chan</a>, and <a href="https://en.wikipedia.org/wiki/LIHKG">LIHKG</a>:

<span style="color: #ff6a00;"><i>*</i><b><i>Disclaimer: </i></b><i>This network graph is provided for illustration purposes only and does not represent actual results from a real study. It serves as a realistic hypothetical example for education. </i></span>
<iframe height="480" src="https://drive.google.com/file/d/1DCNXdp2j35ucYkOH1tsu24AI60_LQEWT/preview" width="640"></iframe>

This network graph provides a detailed visualization of interactions among 30 users across three major discussion boards: 2channel, 4chan, and LIHKG. The <b>nodes</b> in the graph represent both users and discussion boards, with the <b>board nodes in gold</b>.

The<b> color of each user node</b> indicates their primary board of interaction:

<ul>
<li aria-level="1">Light blue nodes correspond to users primarily engaging with the board 2channel</li>
<li aria-level="1">Light green nodes represent users interacting mainly with the board 4chan</li>
<li aria-level="1">Light coral nodes signify users who are most active on the LIHKG board.</li>
</ul>

The<b> edges</b> connecting the nodes represent interactions between users and boards, with the <b>thickness or weight </b>of each edge given in numerical values indicating the frequency of these interactions.

This visualization highlights the distinct user bases associated with each board and provides valuable insights into the patterns of user engagement and cross-platform activity.

<hr/>
<h3><b>Conclusion</b></h3>

Throughout this lesson, we have uncovered the complex interplay between data visualization, visual rhetoric, and framing. By examining early examples of manipulated war photography, such as Fenton's <i>The Valley of the Shadow of Death</i> and O’Sullivan’s <i>Home of a Rebel Sharpshooter</i>, to more recent examples such as<a href="https://www.bbc.com/news/world-asia-india-34991822"> PM Modi’s doctored photo incident</a>, illustrate how visual framing can skew reality,  we saw how visual media, from its inception, has been shaped not just to inform but to persuade and evoke emotion. These examples underscore an important truth: visual representations, far from being neutral mirrors of reality, are imbued with rhetorical intent.

We then explored how these same principles apply to common forms of data visualizations. Whether through timelines, bar charts, or network graphs, the visual presentation of data can clarify complex information but is equally susceptible to manipulation. Techniques such as truncating axes, distorting proportions, or selectively emphasizing data points can subtly, yet powerfully, shape audience perceptions.

Finally, we considered best practices for creating clear, honest, and effective data visualizations. The lesson emphasizes that while visuals can simplify and enhance communication, their design must prioritize accuracy and transparency to maintain credibility. By critically analyzing visual data and understanding its rhetorical dimensions, we become not only better interpreters of information but also more responsible creators.
