# RichTextRepo

<h3>This rich text repo is here to describe to interested parties some of the other code / projects that I have worked on which can't be released online</h3>

<p>For the last few years I have been working at IBM. Here are some of the projects which I worked on, descriptions of the architecture and business purposes of these applications and the technology stacks which they used.</p>

<h4>CMS Customization and Module Development</h4>
<p>I was working on a content management system developing what we call <i>common components</i>. There I was responsible for creating the tools which content builders could use to generate certain IBM layouts compliant with IBM web standards</p>
<ul>
<li>CKEditor</li>
<li>JavaScript / jQuery</li>
<li>Plugin Development for CKEditor</li>
<li>Customization of CKEditor defaults</li>
<li>Development of custom web page authoring templates for the CMS using XSLT and XML</li>
<li>Peer Code Reviews</li>
<li>Agile Development in 2 week sprints</li>
</ul>


<h4>ECC Enterprise Content Catalog Team (Global)</h4>
<p>I was assigned to the ECC which is a catalog of IBM marketing content all stored in Cloudant - the IBM version of the NoSQL database Apache Couch DB</p>
<p>After spending many years on this team, I became very familar with building queries and dynamically generating content on ibm.com pages using JavaScript to load Cloudant content</p>
<ul>
<li>Development of special jQuery widgets to deliver the Cloudant records to corporate pages in specific IBM standards compliant layouts using Mustache.js templates. Customizing and designing these widgets for a variety of different internal customers with many different user and developer requirements.</li>
<li>The developent of the UI to deliver this catalog of content. This JavaScript application included a special sub application to develop the bundles or packages of content compatible with the above widget. This snippet builder became codebase evolving for the use of teams across many global ibm.com sites.</li>
<li>The revamp of the ECC application to use modern build techniques, Gulp, Browserify and NPM</li>
<li>The revamp of the ECC application into a pure JavaScript based stack using node.js and a certain component based JavaScript library</li>
</ul>

<h4>Content And Personalization Team</h4>
<p>Due to the prsonalization nature of my above work with ECC, I was often loaned out to another team dealing with the personalization of pages, ephemeral advertising. We were capturing the customer's IP related to certain industries that they came from and when returning customers reached our pages I developed tools that showed them tailored marketing content based on that industry.</p>
<p>With the advent in 2015 of Watson AI, the team began developing ways to allow Watson to analyze and recommend the best personalized content and I was involved in a project that recommened certain video content from the IBM YouTube channel using the Google YouTube API.</p>
