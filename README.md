# personal-web-project
Personal Web  project

##PWP M.S. 1 Feedback
Great idea for your PWP - your Milestone 1 is complete and meets all requirements. You have a good start with your code, but there are many errors and typos. See the notes below where cleanup and corrections are necessary. You do not need to spend time to correct these, but please take note of the errors. Milestone one passes at [Tier II](https://bootcamp-coders.cnm.edu/projects/personal/rubric/)

###Suggestions
* Create an /images directory at the root of your project, and place all image files here. 
* Create an /css directory at the root of your project, and place all css files here. 
* See Suggestion comments in milestone-1.php and style.css where corrections and cleanup are necessary.

###Code Corrections
1. **milestone-1.php**
  1. lines 3-5: The &lt;head&gt; tag is misplaced.
  2. line 4: Remove the extra " around "text/css". This is breaking your HTML.
  3. lines 5-8: These belong inside the &lt;body&gt; tag.
  4. lines 13, 14: Typo in "clas" - this will break your CSS.
  5. line 24: This tag is incomplete and unclosed. "jpc" should be "jpg". This is breaking your HTML.
  6. line 28: Remove this empty "&lt;&gt;".
  7. line 30: Only one &lt;h1&gt; tag per page. 
  8. line 39: All &lt;li&gt;s need to be enclosed within a single &lt;ul&gt;&lt;/ul&gt; tag.
2. **style.css**
  1. line 4: Extra ;
  2. line 8: Needs a unit of measurement (px, &, or em).
  3. line 12: Missing ;
  4. line 14: Misspelled property. Should be "padding-left".
  5. line 18: Needs space before #666666
  6. line 25: Property misspelled
  7. line 37: Property misspelled
  8. line 39, 40: These rules are misplaced and should be inside {}
  9. line 40: Missing ;
