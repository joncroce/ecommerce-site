<h1>E-Commerce Site</h1>

<p>I came across <a href="https://www.reddit.com/r/webdev/comments/11smo3b/im_currently_in_the_interview_process_for_a_jr/">this reddit post</a> describing a take-home test given to a hiring candidate for a junior front-end development role.</p>

<p><a href="https://joncroce.github.io/ecommerce-site/">This</a> is my attempt to satisfy the requirements, described as follows:</p>

<blockquote>
	<p>This is a front-end engineer programming exercise designed to test the skills required to maintain an eCom site utilizing modern technology native to the browser.</p>
	<p>Your task is to create a hierarchical menu displaying products by collapsible categories with "add to favorites" functionality.</p>
	<ol>
		<li>Create a new github repo and make public via a gh-pages branch</li>
		<li>Create an index.html file. This file should be semantic, accessible, responsive, and discoverable.
			<ul>
				<li>Accessible - Landmark ARIA roles - passes Lighthouse tests - keyboard navigable</li>
				<li>Responsive - Displays on a mobile device and passes Google mobile tests</li>
				<li>Discoverable - SEO fundamentals, SMM Open Graph, and JSON-LD</li>
			</ul>
		<li>Create a single script element. Code all logic within this element. Use no external libraries.
			<ul>
				<li>Using the Fetch promise API get <a href="https://neodigm.github.io/FED_Programming_Challenge/products.json">this JSON file</a>. Combine into a normalized JS data structure.</li>
				<li>Iterate through the data structure and generate the HTML elements and event listeners.</li>
				<li>Hovering over a product name will reveal it's sale price</li>
				<li>Clicking / tapping on any of the products should "Add to Favorites". This state will display a heart toggle (SVG) next to the product. The list of favorite products will persist between sessions in local storage. Mock a Google Analytics custom event to capture that the product has been favorited.</li>
			</ul>
		<li>Create a single style element. Code all CSS within this block. Use no external libraries.
			<ul>
				<li>Use BEM naming</li>
				<li>Use CSS Grid instead of Flexbox</li>
				<li>Try not to use !important</li>
			</ul>
		<li>Test your work on various modern browsers</li>
		<li>Send us the link to your finished repo</li>
	</ol>
	<p>Tips: If you cannot finish simply do the best you can and explain your thought process in the comments. Work at your own pace. We prefer quality over speed.</p>
</blockquote>