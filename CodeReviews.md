# sfntly Code Review #
1.upload your changes to Rietveld
  * from the root directory of your SVN copy run upload.py (https://code.google.com/p/rietveld/wiki/UploadPyUsage)
  * authenticate as necessary. Might need to use the application specific one time password generated at https://accounts.google.com/IssuedAuthSubTokens?#accesscodes
  * enter a subject line using the format "ticket:### description of submission"
<br>2. go to Rietveld<br>
<ul><li><a href='http://codereview.appspot.com/mine'>http://codereview.appspot.com/mine</a>
</li><li>click on the ticket the change you just submitted<br>
<ul><li>"Edit Issue"<br>
</li><li>add reviewers<br>
<ul><li>at least one reviewer should be a sfntly project committer<br>
</li></ul></li><li>add any message<br>
</li><li>click "Publish All My Drafts"<br>
<br>3. Wait for feedback<br>
</li></ul></li><li>exchange comments with the reviewer<br>
<br>4. Correct any issues<br>
</li><li>make changes in your local SVN copy<br>
</li><li>after doing so update the code review<br>
</li><li>run upload.py -i ISSUE#<br>
<ul><li>the ISSUE# is the number you see on the Rietveld code review site<br>
</li></ul></li><li>repeat as necessary<br>
<br>5. Reviewer should set the overall issue comment to "LGTM" when all is ok<br>
</li><li>submitter should not submit code until review is complete<br>
<br>6. Once the review has been completed submit the changes to sfntly using the regular svn commands</li></ul>

<br>7. Mark as fixed any open issue related to this and note the change list