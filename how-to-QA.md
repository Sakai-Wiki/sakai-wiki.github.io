<ac:layout>
    <ac:layout-section ac:type="two_equal">
        <ac:layout-cell>
            <ac:structured-macro ac:name="toc" ac:schema-version="1" ac:macro-id="716fe56b-b0bc-4b7a-bb4a-7eab442efeda" />
        </ac:layout-cell>
        <ac:layout-cell>
            <h3>Current QA activities in this column</h3>
            <p><a class="external-link" style="text-decoration: underline;" href="http://nightly2.sakaiproject.org/" rel="nofollow">QA Servers</a></p>
        </ac:layout-cell>
    </ac:layout-section>
    <ac:layout-section ac:type="single">
        <ac:layout-cell>
            <div class="wiki-content">
                <h3>General Information about QA&nbsp;</h3>
                <h4>Purpose</h4>
                <p>QA stands for Quality Assurance. In this context the QA mission is primarily to uncover and report software bugs, to verify fixes to software bugs, and to test for regressions. &nbsp;Regressions are features that worked in previous versions, but are broken in the current version.</p>
                <h4>Pre-requisites for participating</h4>
                <p><strong><span style="color: rgb(51,153,102);">Required</span></strong>&nbsp;- a Jira account is required. Sign up at&nbsp;<a class="external-link" style="text-decoration: underline;" href="https://jira.sakaiproject.org/" rel="nofollow">https://jira.sakaiproject.org</a></p>
                <p><strong><span style="color: rgb(255,153,0);">Video</span></strong>:&nbsp;<a class="external-link" style="text-decoration: underline;" href="http://www.screencast.com/t/cjGFeAu27" rel="nofollow">How to Create a Jira</a>&nbsp;(3:26 minutes)</p>
                <p><strong><span style="color: rgb(51,153,102);">Required</span></strong>&nbsp;-&nbsp;Join Sakai QA email group (<a style="text-decoration: none;" rel="nofollow">sakai-qa@apereo.org</a>) or Sakai Dev group (<a style="text-decoration: none;" rel="nofollow">sakai-dev@apereo.org</a>) to keep up to date with the latest announcements and ways to help with the testing effort.</p>
                <p><strong><span style="color: rgb(255,102,0);">Optional</span></strong>&nbsp;-&nbsp;<strong>Experienced Testers</strong>&nbsp;- Although, you do not need special permissions to test fixes and to comment on Jira issues, you can not mark the Jira as having its testing completed. To mark the Jira as completed, you need access to a &quot;Tested&quot; button which indicates successful testing of a Jira issue. This button is only available if you are a member of the Jira QA group. Contact&nbsp;<a class="external-link" style="text-decoration: underline;" href="mailto:sakaicoordinator@apereo.org" rel="nofollow">sakaicoordinator@apereo.org</a>&nbsp;for more information.</p>
                <p><strong><span style="color: rgb(0,0,255);">Hints</span></strong>&nbsp;- Our primary tools are Jira, Google docs spreadsheets, and QA servers. Learning how to use Jira and what the fields represent is well worth the time.</p>
                <h4>Ways to Participate</h4>
                <ul>
                    <li>Verify bugs that have been fixed.</li>
                    <li>Test new features.</li>
                    <li>Test existing features to assure changes around them haven't introduced bugs (regressions).</li>
                    <li>Create Regression scripts (i.e. step-by-step instructions for performing regression tests.)</li>
                    <li>Release testing - testing alpha, beta, and release candidate versions before software is made generally available (GA aka &quot;General Availability&quot; aka production ready).&nbsp;</li>
                    <li>Proofread. Make suggestions. Create short videos.&nbsp;</li>
                    <li>Ask and answer questions on the email groups.&nbsp;</li>
                    <li>Attend the QA meetings to bring up issues that need attention, and to help plan testing for releases.</li>
                    <li>Expert QA knowledge needed - special skills are needed for some types of QA testing.</li>
                </ul>
                <h4>When to Participate</h4>
                <ul>
                    <li>Anytime. We are almost in constant need of QA testing of one form or another.&nbsp;<a class="external-link" style="text-decoration: underline;" href="mailto:sakaicoordinator@apereo.org" rel="nofollow">Contact the sakaicoordinator@apereo.org</a>&nbsp;for help getting started.</li>
                    <li>Major Releases - Sakai 11, Sakai 12 and Sakai 19 are all examples of major releases. Major releases typically include significant upgrades to existing features and the addition of new features.</li>
                    <li>Maintenance Releases - Sakai 11.4 and Sakai 12.6 are examples of maintenance releases.&nbsp;</li>
                </ul>
                <h4>Verifying bug fixes</h4>
                <p>Testing either takes place on&nbsp;<a class="external-link" style="text-decoration: underline;" href="http://nightly2.sakaiproject.org/" rel="nofollow">a nightly server, usually trunk,&nbsp;</a>, or on a QA server that is announced when community testing for major or maintenance releases is scheduled.&nbsp;Please be aware that nightly servers are refreshed daily, at midnight Eastern time (-4 or -5 GMT). Please plan your testing appropriately.&nbsp;</p>
                <p><br /></p>
                <p>Jira bugs which have a resolution of &quot;Fixed&quot; and a status of &quot;Resolved&quot; are ready for testing. If testing is successful click the Tested button. The status will change to Verified. If you don't see a Tested button, even with the correct status and resolution, you may not have permissions in Jira to see the button. Contact&nbsp;<a class="external-link" style="text-decoration: underline;" href="mailto:sakaicoordinator@apereo.org" rel="nofollow">sakaicoordinator@apereo.org</a>&nbsp;to request this permission.</p>
                <p><span class="confluence-embedded-file-wrapper">
                        <ac:image>
                            <ri:url ri:value="https://confluence.sakaiproject.org/download/attachments/83035214/Tested_button.png?version=1&amp;modificationDate=1378202160000&amp;api=v2" />
                        </ac:image>
                    </span></p>
                <p>In your comments make sure to include which OS/browsers you tested and the Revision number of trunk. The Revision number is important because trunk changes frequently. Look at the bottom of your browser window for the Revision number.&nbsp;</p>
                <p><span class="confluence-embedded-file-wrapper">
                        <ac:image>
                            <ri:url ri:value="https://confluence.sakaiproject.org/download/attachments/83035214/Revision_example.png?version=1&amp;modificationDate=1378202897000&amp;api=v2" />
                        </ac:image>
                    </span></p>
                <p>Notes: Some issues may require testing in more than one OS /Browser combination.&nbsp;</p>
                <h4>Special Case: Master (formerly trunk vs Branch)</h4>
                <p>The Master branch (previously known as Trunk) has the most recent source code, and is constantly changing as developers contribute fixes and new features. At some point, when we are getting ready to release Sakai as a community-supported version (aka general availability or production release), we create a branch. A branch is a copy of master at a certain point in time, a snapshot. By doing this, we can exercise more control over what goes into a release. We name a branch to correspond with the release. For Sakai 12.0 release we have a 12.0 branch, which we sometimes also refer to as 12.x. For Sakai 19.0 release we have a 19 branch, also called 19.x .&nbsp; Features and fixes almost always start in master (more than 99% of the time. Exceptions are rare.) We test features in master and then when they are verified to work, if they should be included in a branch, we merge them into the branch and re-test the fixes, since the environment between master and the branches can diverge significantly. A fix that works in master, may not work in the branch (although in most cases it does.) Since we do not have enough QA resources to retest every fix, we focus on getting at least all the blocker priority issues retested.</p>
                <p>We include in JIRA a status that indicates the state of the ticket with respect to the branch. For example: 12 status. When it is set to Resolved it means that the fix has been merged into the Sakai 12.x branch. Verified means that it has been tested after merging into 12.x . This can be confusing, until you get used to it, because it means that there are at least two fields on a&nbsp;JIRA ticket that have the potential to be set as Resolved or Verified, the main Status of the ticket (see image above), and the branch status. There are only 2 versions of Sakai in development at any one time. Currently that is 12 and 19, therefore we have a 12 status field and 19 status field. When Sakai 19 is released, we will drop support for Sakai 11 and there will be an 19 status field and a 20 status field.</p>
                <p>As a QA tester, once you understand what the fields mean, it is okay to set the status yourself to Verified, on both the overall&nbsp;JIRA and for the branch.</p>
                <p><br /></p>
                <p><span class="confluence-embedded-file-wrapper">
                        <ac:image>
                            <ri:url ri:value="https://confluence.sakaiproject.org/download/attachments/83035214/10_status_options.png?version=1&amp;modificationDate=1434985861000&amp;api=v2" />
                        </ac:image>
                    </span></p>
                <h4>A bug that is supposed to be fixed, isn't</h4>
                <p>If you are verifying a fix and it fails then reopen the issue by clicking the Reopen button. This indicates to the developer that there is more work to be done. If you are not sure if the issue should be reopened then simply leave a comment. Make sure to include the exact steps of how it failed, what server you were on, the revision number if testing was done on trunk, browser/os, etc.</p>
                <h4>Test New Features</h4>
                <p>Testing new features is essentially the same as testing for bug fixes. You still want to click the Tested button to move the issue to Verified status if all the testing passes, and Reopen or add comments if you find bugs. Sometimes there are debates about new features and what constitutes a &quot;bug&quot;. Those debates happen in the Jira comments and sometimes are brought to other groups like the Sakai Core team for broader discussion, as appropriate/relevant.&nbsp;</p>
                <h4>Regression testing</h4>
                <p>Regression testing is a kind of detailed testing. Regressions are features that worked in previous versions of Sakai, but now are broken in the current version. It It is very important to uncover these kinds of problems as soon as possible.&nbsp;</p>
                <p>The most up-to-date list of tools for which we have Regression scripts (steps for testing features manually) is kept in Apereo's Google drive. The most recent set is for&nbsp;<a class="external-link" style="text-decoration: underline;" href="https://docs.google.com/spreadsheets/d/1xf0gQ6zvsh76ScMkeK4AsQqmGZr9tO6xPjzyE4-SviU/edit#gid=1" rel="nofollow">Sakai 19 RC.1</a></p>
                <h4><a class="external-link" style="text-decoration: underline;" href="http://bit.ly/18MGG0j" rel="nofollow">Sakai 11 Scripts-do we have updated copies?</a></h4>
                <h4>Release testing - QA Test Hubs</h4>
                <p>Our goal is to have testing happen as much as possible throughout the Sakai version lifecycle (verifying bug fixes in trunk, testing new features, and regression testing the latest release). However, when we are getting close to having a tagged release (e.g. 12.6, 19.0, 19.1RC, etc) we choose specific periods of time to test, with a Test plan and focus. We call these testing efforts &quot;Test Fests&quot;. We have multiple Test Fests to get out a release. Unless otherwise specified we have one &quot;Test Fest&quot; per phase of the release. For example, we might have several Beta versions of the software before the Sakai core team feels confident that it is ready for release. Typically, we then have two or three Release Candidates of the software. A Release Candidate is a version of the software, which if it passes QA testing and Developer scrutiny, will become the next official community release. Each of these Beta releases and Release candidates is a phase of our Software Release process.&nbsp;</p>
                <p>What makes a Test Fest unique is that we create a Test plan to guide our testing, a defined period of time to complete the testing, and a review process to assess the state of our testing results. Test Fest's typically take a concentrated effort and we like to have as many testers as possible helping in the effort, sometimes with multiple testers focusing on the same functional areas to provide the highest confidence level we can reasonably achieve. Test Fests are almost always carried out on&nbsp;<a style="text-decoration: underline;" href="https://confluence.sakaiproject.org/display/QA/Test+Instances">special QA test servers</a>&nbsp;which have been updated with the correct version of the software which needs testing. The Test Plan will indicate which QA servers are available for testing.&nbsp;</p>
                <h4>QA team meetings</h4>
                <p>QA Planning Meetings Thursdays 5:30 PM EST BigBlueButton Sakai QA Room.&nbsp;</p>
                <p>QA Test Fest Meetings Fridays 10 AM EST BigBlueButton Sakai QA Room&nbsp;&nbsp;</p>
                <h4>Expert QA knowledge</h4>
                <ul>
                    <li>Accessibility Testing</li>
                    <li>Localization Testing (different languages)</li>
                    <li>Review of patches and fixes</li>
                    <li>Testing locally</li>
                    <li>Automated testing</li>
                    <li>Security testing (requires special permission)</li>
                </ul>
                <h4>General Testing Tips</h4>
                <p><br /></p>
                <div class="conf-macro output-block">
                    <h5>Overview</h5>
                    <p><span style="color: rgb(0,0,0);">This section serves to provide general testing tips for web applications. It provides basic tests for different elements in web applications to help users think about different ways to test. It is not meant to provide comprehensive documentation on every way to test.</span></p>
                    <h5>Categorized tips</h5>
                    <h6><span style="color: rgb(0,0,0);">Data variations</span></h6>
                    <p>Variations in data that should be used throughout the application in every location that strings can be entered.</p>
                    <ul>
                        <li>Special characters in text ~!@#$%^&amp;*()</li>
                        <li>Non-Latin characters (Cyrillic, Arabic, Japanese, Chinese, Klingon, etc.)</li>
                        <li>Languages from right to left (Arabic, Hebrew) [<a class="external-link" style="text-decoration: underline;" href="http://www.lipsum.com/" rel="nofollow">http://www.lipsum.com</a><span>&nbsp;</span>is a good site to get sample text for both non-latin characters and languages reading from right to left]</li>
                        <li>Latin characters with diacritical marks</li>
                        <li>Latin characters using ligatures</li>
                        <li>Very long strings</li>
                        <li>Single character strings</li>
                        <li>Scripts/HTML tags<ul>
                                <li>&lt;script&gt;alert(&quot;xss&quot;);&lt;/script&gt;</li>
                                <li>Content should be handled gracefully, but not executed when displayed, unless explicitly stated for a feature</li>
                            </ul>
                        </li>
                    </ul>
                    <h6>Form testing tips</h6>
                    <ul>
                        <li>Submit with no form values</li>
                        <li>Submit without required fields filled out</li>
                        <li>Submit with improperly formed values (i.e. an improperly formed email in an email address field)</li>
                        <li>Submit with Data variations (see Data Variations section)</li>
                    </ul>
                    <h6>Login screen testing tips</h6>
                    <ul>
                        <li>Submit with no values</li>
                        <li>Valid username, invalid password</li>
                        <li>Valid username, valid password</li>
                        <li>Invalid username</li>
                        <li>Valid username, no password</li>
                    </ul>
                    <h6>Drop Down menus</h6>
                    <ul>
                        <li>Drop down is properly sized for menu options</li>
                        <li>Default menu option is displayed in drop down on page load</li>
                        <li>Selected menu option is displayed in drop down after clicking off menu</li>
                        <li>Drop down menu can be navigated through with keyboard and mouse</li>
                        <li>Drop down menu appropriately resizes vertically on small screen resolutions</li>
                        <li>Entering a character selects the first menu option starting with that character</li>
                    </ul>
                    <h6>Combo box</h6>
                    <ul>
                        <li>Combo box is properly sized for menu options</li>
                        <li>Default menu option is displayed in drop down on page load</li>
                        <li>Can select single item</li>
                        <li>Can select multiple items in list</li>
                        <li>Can select non-contiguous items</li>
                        <li>Drop down menu can be navigated through with keyboard and mouse</li>
                        <li>Drop down menu appropriately resizes vertically on small screen resolutions</li>
                        <li>Entering a character selects the first menu option starting with that character</li>
                    </ul>
                </div>
                <p><br /></p>
                <p><br /></p>
                <p><u><strong>Onboarding New Members:</strong></u></p>
                <p>Here is the link to the onboarding manual for Sakais QA Team:&nbsp;<a class="external-link" style="text-decoration: underline;" href="https://docs.google.com/document/d/1GXM4pSwyCvyUrThTFovK_XehiFWmdYYH5XxO_ni39js/edit?usp=sharing" rel="nofollow">https://docs.google.com/document/d/1GXM4pSwyCvyUrThTFovK_XehiFWmdYYH5XxO_ni39js/edit?usp=sharing</a></p>
            </div>
        </ac:layout-cell>
    </ac:layout-section>
</ac:layout>