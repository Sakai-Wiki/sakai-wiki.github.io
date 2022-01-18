# **JIRA Authoring 101**
## **Part 1: Detective Work**
### **Get familiar with your issue.**
1. Find an issue - often this happens on a local Sakai environment at your institution.
1. Replicate the issue, ask:
   1. Can it be reproduced consistently?
   1. Are specific conditions needed to trigger it?  Identify them if so.
   1. Does it affect multiple Sakai tools?  If yes, which ones?
      1. Examples: Date picker and Rich-Text Editor are in many tools
   1. Also, take note of steps to reproduce - you will need these later!
1. Replicate the issue elsewhere.
   1. Try different nightly servers.  If it happens on Trunk (master), does it also happen on Sakai 12 Jira Testing server?  If it seems new, test back a version! Does it happen on Sakai 11.x maintenance?
   1. Some issues require specific Sakai properties to be set - if something appears to be missing, ask in Slack or the sakai-dev mailing list if the necessary properties are present on the server where you need to test.
### **Find out if anyone else already knows about it.**
1. Now that you know where it happens, [search for the issue in Sakai JIRAs](https://jira.sakaiproject.org/issues/?jql=)!
1. Some ways to search (with examples):
   1. With a filter someone has provided - access the link!
   1. Search by **tool** (or something like **Accessibility** or **Internationalization**): **Component = [tool name]**
   1. Search in the text: **text ~ "multiple choice"**
   1. Find jiras by status: **status = Open**
   1. Find jiras assigned to you: **assignee = currentUser()**
   1. Mix it up, e.g., **component = Accessibility AND component = "Tests & Quizzes (Samigo)" AND text ~ "multiple choice" AND status = Open**
## **Part 2: Support or Report**
### **If the issue exists in JIRA already:**
1. Make sure it has complete information for it to be addressed.  If not, add information in the *Description* and/or *Testing Steps*.
1. **Start watching** it.
1. Add a **Comment** to let others know you’ve experienced it too (you can also provide information in comments if it does not belong in the Description or Testing Steps).
1. **Link** to related issues by selecting the **More** menu, then **Link**.  Search for and select or enter the JIRA numbers (e.g. SAK-#####) to add related jiras.  Links are extremely helpful to ensure that people can find the information they need in JIRA and most importantly, when fixes for several issues need to be applied together, they are all included!
1. Select **Vote for this issue** to vote for it.
### **If it does not exist, create a jira:**
[Watch a video for how to create a jira.](https://www.screencast.com/t/EhrDBbUocWuR)
#### **General Tab**
1. **Issue type:** Bug if it is not behaving correctly, Feature Request if it is behaving as expected, but needs improvement.
1. **Summary:** The title (brief description of issue)
1. **Priority:** Defaults to **Major**; if not sure, leave it.  **Blocker** is for something that totally destroys functionality and will prevent release of the affected Sakai version.
1. **Components:** Affected **tools** or **features** (e.g. Accessibility, Internationalization)
1. **Affects versions:** Include ALL the most recent Sakai versions it affects.
1. **Assignee:** Leave default (**Automatic**)
1. **Environment** includes:
   1. URLs of server(s) where you tested it,
   1. Computer operating system,
   1. Internet browser and version,
   1. If you are using additional technology (such as a screen reader), the software and version.
1. **Description:** Try to explain it as clearly as possible.  If you have screen shots, you can attach these and embed them in the description (see below, the **Tips** under the description of the **Testing Tab**, for steps to embed).
1. **Attachment:** Screen shots, a text file with a copy of a bug report (if one appears while reproducing the issue) or other files (e.g., an exported quiz for someone to reproduce the issue) - you can embed or link these attachments right in the jira text too!
1. **Security Level:** Usually leave default (None) - security jiras are sensitive issues like holes for hackers to exploit.
1. **Labels:** Optional - these can help you search for the issue, some examples: **TL** if you want Teaching & Learning call to look at it, **Accessibility** or **a11y**, **Internationalization** or **i18n**.
1. **Fix Version/s:** Leave default (empty) - these get added after the issue is fixed.
#### **Testing Tab**
Remember those testing steps/steps to reproduce?  Here’s where they go!

**Tips:**

1. Pretend you are explaining to someone who is coming to Sakai (or your tool) for the first time.  Be as thorough as possible!
1. Use a numbered list for the steps.  If authoring in **Text**, enter **#** with a space after it on each line to make a numbered list item.
1. If it isn’t obvious, indicate the **desired behavior** also for bugs (what should happen when fixed?)
1. If you added attachments, insert them where appropriate (it really helps to have a screen shot inline with the text!)  If authoring in **Text**, place the attachment name in between two exclamation marks, e.g. **!screenshot.png!**  For large screen shots, you can embed a thumbnail image, e.g.: **!screenshot.png|thumbnail!**
#### **After Creation**
After creating the jira, **Link** to related issues by selecting the **More** menu, then **Link**.  Search for and select or enter the JIRA numbers (e.g. SAK-#####) to add related jiras.  Links are extremely helpful to ensure that people can find the information they need in JIRA and most importantly, when fixes for several issues need to be applied together, they are all included!
