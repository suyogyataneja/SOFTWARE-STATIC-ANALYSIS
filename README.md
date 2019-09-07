# SOFTWARE-STATIC-ANALYSIS
Leveraging static analysis tools to pinpoint security issues of software
applications
Tasks
1. Choose a static analysis tool
There are quite a lot of static analyzers available in the community. Here I just list
several well-known examples that the students can choose from. The student can still
choose other tools including other language-based tools.
Ø Java: FindBugs
Ø Android: AndroBugs
Ø C++: RATS, Flawfinder
2. Understanding the selected tool
The students should explore the selected tool in various aspects, attempting to
summarise the capabilities provided by the tool. One way to identify such capabilities
could be to go through all the input options that the tool provides.
3. Finding target code to analysis
In this step, the students should choose at least one project (or one Android app) to
perform their analysis and that project should contain security issues. Github is a great
source that the students can leverage to finding target projects. The following
screenshots demonstrate various projects that are mainly written in Java and C++,
respectively.
4. Launch the selected analyzing tool to the selected repositories (or
Android apps)
After selecting the to-be-tested projects, the next step is to launch the selected
static tool to analyse the source code of those selected projects.
The students should clearly describe the setup of their experiments, e.g., how the
selected tool is launched, what is the inputs provided? The students are also expected
to justify the complexity of the selected projects. How big is the selected projects?
Ideally, the more complex the projects selected (e.g., top 10 Java projects hosted on
Github), the higher score the assessment will be.
5. Summarize the analyzing results of the aforementioned experiments
After launching the static tool on the selected projects, the tool should generate
some results, ideally security issues related to the analysed projects. The students
should then summarize those results in various means, attempting to represent those
results in more understandable ways. Last but not the least, the students should also
provide some insights that are learned from the experiments and could be useful for
other code analysers.
