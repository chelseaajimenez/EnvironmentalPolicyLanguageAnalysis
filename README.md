<h1>Ten Strands Environmental Policy Language Analysis</h1>

<h2> Project Description</h2>

This project partners with Ten Strands, a nonprofit dedicated to advancing climate literacy in California school districts, and analyzes the language used in environmental board policies passed by California’s K-12 public school districts to determine whether it correlates with evidence of environmental and climate action across four key areas: campus, curriculum, community, and culture.

As part of this project, I analyzed two environmental board policies:

<ul>
  <li><b>AR 7111: Evaluating Existing Buildings </b></li>
  <li><b>BP 3511: Energy and Water Management </b></li>
</ul>

The dataset includes over ten environmental board commitments and more than thirty indicators of environmental and climate action. Initial quantitative analysis has explored the correlation between the number of commitments and observable actions, but large-scale qualitative analysis of policy language remains an open area of research.  

By identifying specific language patterns that signal a higher likelihood of action, this project aims to uncover how policy wording influences real-world implementation. Insights from this analysis can help educators, policymakers, and advocates craft more effective policies that drive meaningful climate action in schools.  

<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Pandas</b>
- <b>Natural Language Processing (NLP)</b>

<h2>Project Setup and Data Processing </h2>
I followed a structured data collection and processing workflow to analyze environmental policy language. This involved gathering policy documents, organizing them systematically, extracting relevant text, and preparing the data for analysis.

<h3> 1. <b>Collecting and Organizing Policy Documents</b> </h3>

I first gathered board policy documents from California K-12 public school districts, focusing on environmental commitments. Each document was stored using a standardized naming convention to maintain consistency and facilitate easy retrieval. Policies were labeled based on their policy number (BP_AR_XXXX) to ensure proper identification.


<h3> 2.  <b> Structuring Data with Google Sheets</b>  </h3>
  
To keep track of policy documents, I created a Google Sheet to document essential details, including:

<ul>
  <li><b>Policy Name & Number</b></li>
  <li><b>School District Name</b></li>
  <li><b>File Path for PDF Storage</b></li>
</ul>

<h3> 3. <b>Extracting and Cleaning Policy Text</b> </h3>

Once the policies were collected, I extracted the text from PDFs for analysis. This required:

<ul>
  <li>Converting policy documents into <b>machine-readable text</b></li>
  <li>Cleaning the extracted text by <b>removing formatting inconsistencies</b></li>
  <li>Standardizing text structures to ensure <b>accurate analysis</b></li>
</ul>

This step helped prepare the dataset for <b>Natural Language Processing (NLP)</b> techniques, allowing for further investigation of policy language.

<h3> 4. <b>Organizing Cleaned Data</b> </h3>

After text extraction and cleaning, I stored the processed data in a structured format, ensuring it was:

<ul>
  <li><b>Consistently labeled</b> based on the original policy document</li>
  <li>Formatted as <b>structured text data</b> for analysis</li>
  <li>Saved in a <b>separate folder</b> for easy accessibility and reproducibility</li>
</ul>

<h2> Methodology </h2>

To analyze environmental policy language, I applied <b>Natural Language Processing (NLP)</b> techniques, focusing on <b>text extraction, word frequency analysis, and correlation studies</b>.

<h3> 1. <b>Text Preprocessing</b> </h3>

<ul>
  <li>Cleaned and standardized policy text data.</li>
  <li>Removed unnecessary formatting and special characters.</li>
</ul>

<h3> 2. <b>Word Frequency Analysis</b> </h3>

<ul>
  <li>Identified the most frequently used terms related to <b>sustainability and environmental action</b>.</li>
  <li>Used this to detect <b>key themes</b> in policy language.</li>
</ul>

<h3> 3. <b>Data Visualization</b> </h3>

<ul>
  <li>Mapped the <b>distribution of sustainability indicators</b> across school districts.</li>
  <li>Analyzed <b>policy sustainability scores</b> in relation to <b>student enrollment</b>.</li>
</ul>

<h3> 4. <b>Correlation Analysis</b> </h3>

<ul>
  <li>Examined whether <b>stronger policy wording</b> correlated with <b>higher sustainability action</b>.</li>
  <li>Compared <b>policy terms</b> with <b>district-wide sustainability efforts</b>.</li>
</ul>

<h2> Key Findings & Insights </h2>

<ul>
  <li>Strongly worded policies often align with <b>higher levels of environmental action</b>.</li>
  <li>Certain <b>keywords</b> (e.g., “sustainability,” “carbon neutrality”) correlate with proactive school district initiatives.</li>
  <li>Some school districts have <b>comprehensive policies</b> yet lack implementation.</li>
</ul>






<p align="center">
BP3511 Keyword Analysis: Word Frequency Word Cloud <br/>
<img src="https://i.imgur.com/DELVNcp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

The word cloud above visualizes the most frequently occurring terms in BP 3511, a policy focused on energy efficiency and environmental sustainability in school operations. The prominence of words like district, management, water, and website suggests an emphasis on administrative oversight, resource management, and digital accessibility rather than direct sustainability actions. The presence of shall reflects the formal directive language typical in policy documents, while environmental terms like energy and resource appear less frequently. Mentions of superintendent and designee indicate that responsibility for policy execution is assigned to specific roles. The focus on management and compliance rather than explicit sustainability measures aligns with broader findings that strong policy wording does not always translate into meaningful environmental action.
<br />
<br />
<p align="center">
BP 3511 Top 20 Words  <br/>
<img src="https://i.imgur.com/8iv71P5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

The bar chart above displays the top 20 most frequently used words across school district board policies. Terms like district, water, shall, and management appear most often, reflecting a strong emphasis on administrative oversight, regulatory language, and resource management rather than direct sustainability actions. Words related to environmental efforts, such as energy, conservation, and storm, appear but at lower frequencies, suggesting that while policies mention sustainability, they may prioritize procedural and compliance language over actionable commitments.
<br />
<br />
<p align="center">
BP3511 Indicator Summary <br/>
<img src="https://i.imgur.com/tXPdy2u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

The stacked bar chart above compares the presence (1) and absence (0) of various sustainability initiatives across school districts. Indicators like Building Electrification, Energy Efficiency, and On-Site Renewables show a relatively balanced distribution, whereas initiatives like School Gardens and EV Chargers for Parking have significantly fewer implementations.

The predominance of red (0s) in most indicators suggests that while environmental policies may acknowledge sustainability efforts, actual implementation remains limited. This supports the broader finding that strong policy language does not necessarily translate into real-world environmental action, highlighting the need for additional funding, incentives, and accountability measures to drive meaningful change.
<br />
<br />
<p align="center">
BP3511 Scoville Language Menu of Possible Revisions for Strategy 1:  <br/>
<img src="https://i.imgur.com/5BKsunm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
The table above categorizes policy language on a Scoville scale of commitment: Mild, Medium, and Spicy. "Mild" policies use generic language with minimal actionable directives, while "Spicy" policies include specific commitments, clear timelines, and defined actions such as installing renewable energy upgrades and ensuring energy-efficient construction.
<br />
<br />
  <p align="center">
BP3511 Strategy 1: Energy and Water Conservation and Management:  <br/>
<img src="https://i.imgur.com/j3YdWee.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    
The chart above classifies policies based on their commitment level to energy and water conservation. The majority fall under the Spicy category, indicating that many policies use strong language to convey sustainability commitments. However, previous findings suggest that stronger language does not necessarily correlate with real-world implementation, reinforcing the need for accountability measures and resource allocation to ensure meaningful climate action.
</p>

  <h2> Conclusion </h2>
This analysis of school district environmental policies reveals key insights into how policy language aligns with real-world sustainability actions. While many policies use strong language (Spicy commitment level), there is no clear correlation between policy wording and actual implementation. This suggests that policy strength alone is not enough to drive meaningful environmental action in schools.

The word frequency analysis showed that administrative and compliance-related terms (e.g., "district," "management," "shall") dominate policy language, while direct action terms like "renewable energy" and "conservation" appear less frequently. The distribution of sustainability initiatives across districts further highlights inconsistencies in implementation, with certain actions such as school gardens and EV chargers being significantly underrepresented.

Ultimately, these findings emphasize the gap between policy language and execution. While strong wording may indicate intent, other factors such as funding, leadership, and community engagement likely play a larger role in determining whether sustainability initiatives are successfully implemented. These insights help guide nonprofits and policymakers in refining their strategies, ensuring that resources are directed toward measurable and impactful environmental efforts rather than just policy improvements.
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
