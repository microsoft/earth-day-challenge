# Microsoft Earth Day Challenge
We’re excited that you’ve decided to share your idea(s) on how to use AI to save and protect the Earth. Here are the steps for submitting your idea and getting featured on our blog:

1)	Complete the [Earth Day Cloud Skills Challenge](https://www.microsoft.com/en-us/learncloudchallenge/e71a0acd-8463-4651-a001-0bb0e9dc62e5) between 4/5/2021 - 4/30/2021. We will plant a tree for each customer to complete the challenge, up to 50 trees total.
2)	Use the skills that you learned during the Cloud Skills Challenge to come up with an idea. Please include the following to be featured on the blog*:
            a.	Submit idea and working code to [Github repository](https://github.com/microsoft/earth-day-challenge)
            b.	Include [MS Learn ID](https://docs.microsoft.com/en-us/learn/) in notes section of submission
3)	Customers with an eligible entry will receive a digital Acclaim Sustainability badge by email, and be featured on our [Technology blog](https://cloudblogs.microsoft.com/industry-blog/microsoft-in-business/technology/) on May 24.

*This offer is open only to US developers employed in the field of software research or software sales and development. You must legally reside in the 50 United States (including the District of Columbia), and be 18 years of age or older to participate. You must have registered for and completed the Earth Day Cloud Skills Challenge learning path using same email address as below for validation. Submissions must include idea, code and MS Learn ID to be eligible. All code submitted must be functional.  Only one idea with accompanying working code will be promoted in the blog per person. Submitted code must utilize skills from Earth Day Cloud Skills Challenge learning path and be added into this Github repository (www.github.com/microsoft/earth-day-challenge) to be featured in the blog post.  Entries must be submitted between 4/5/21-4/30/21 at 11:59 pm PST.  By submitting your entry to Github, you acknowledge and agree that you are bound by the GitHub Terms and Conditions (https://docs.github.com/en/github/site-policy/github-terms-of-service#d-user-generated-content) and that you will not receive any payment or other monetary compensation from Microsoft for your entry.  In addition, you grant to Microsoft the right to use your name and professional title for the purpose of featuring your entry in the blog post. Microsoft reserves the right to reject any entries that do not meet the foregoing criteria or are considered inappropriate for any reason.

# How to Create Project?

Once you decide what you gonna call you project, follow the steps to create your project folder and start coding:

First we create a fork of the main repo and then clone it to disk and create a branch to work in. The instructions below assume you have the git command line on your machine. If you're more comfortable in a GUI git client, you can use that too (we recommend SourceTree).

1. Create a fork of the main repo
   - Navigate to the git repo at: <https://github.com/microsoft/earth-day-challenge/>
   - Click the Fork button at the top right of the page and then choose the account you want to create the fork in. 
2. Clone your new fork to your local machine
   - `git clone https://github.com/microsoft/earth-day-challenge/`
   - `cd earth-day-challenge`
3. Create a new branch for your work. It is a best practice to never work directly on the master branch
   - `git branch MyWork`
   - `git checkout MyWork`
4. Add a new top level folder to the WTH repo using the next available number in sequence
   - `mkdir <your MS Learn ID>-<Your Project Name>`
5. Within your new folder, create the  directory structure like this:
	- `../deployment`
		- `/Solutions`
	- `../presentation`
	- `../test`
		
		`
 ### Files and Folders
Now that you've created the directory structure above, create folling files/instuctions:
- `../`
	- Project Description (README.md)
	- Deployment Instructions
	- Architecture diagrams 
	-etc.


## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
