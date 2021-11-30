<h1>Master Template | November 30, 2021</h1>
<h2>&lt;tr&gt; based modules</h2>
<p>Table row based modules need to be placed in a containing table (like the one available in the boilerplate). Then, module rows can be stacked.</p>
<p>This helps eliminate white line issues in Outlook.</p>

<h2>Dark Mode Styles</h2>
<p>The master template now includes dark mode styles, images, and icons. Dark mode works differently across email clients. 
These different renderings have been accounted for and should require little or no change in how email specialists update modules.</p>
<ul>
<li>Logos and icons have been updated to work in all versions of dark mode.</li>
<li>Hero XL Module has been updated to work in all versions of dark mode.</li>
</ul>
<h2>Better Accessibility</h2>
<p>Accessibility enhancements have been added to the email template, including the following:</p>
<h3>Email Design</h3>
<ul>
<li>Left justify large blocks of email copy</li>
<li>Minimum font size of 14px</li>
<li>Optimized line spacing (150 to 200% of font size)</li>
<li>High color contrast between font and background color</li>
</ul>
<h3>Email Code</h3>
<ul>
<li>Accessible tables</li>
<ul>
<li>Inclusion of role attributes on tables and buttons</li>
</ul>
<li>Relative font-size (em, rem, and %) that can be adjusted by the user settings.</li>
<li>Use of semantic HTML elements</li>
<ul>
<li>Headlines wrapped in header elements (h1, h2, h3, etc.)</li>
<li>Copy wrapped in paragraph elements (p)</li>
<li>Blockquotes used for student / graduate quotes</li>
</ul>
<li>Alt tags included on images</li>
<li>Hover effects on buttons and links</li>
</ul>

<p>Email specialists will need to add and update alt tags to images (jump to alt tag guide), include html elements around text, and make sure roles are on all tables.</p>

<h2>Coding Enhancements</h2>
<p>One of the most important aspects of the new email master template update is its ease of use. Modules were enhanced for quicker workflow when creating a new campaign.</p>
<ul>
<li>Simplified table nesting and removal of duplicate styles and unnecessary inline css removed</li>
<li>CTA buttons no longer have one version for web and one version for Outlook; consolidated into one block of code</li>
<li>Background image code is simplified; only necessary to update two URLs</li>
<li>Better mobile responsiveness for background images</li>
<li>Use of CSS padding instead of nested tables with varying widths</li>
<li>Use of em and rem units for font-size and line-height</li>
<li>Better control of preheader code; less visibility in email client rendering</li>
</ul>
