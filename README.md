# facteaser
A Knime workflow to parse full-text HTML outputs from Factiva.

This is a Knime workflow that converts HTML outputs saved from Factiva (a subscription-based news database) into a tabular format so that it can be passed to text analysis software.

You will need to install Knime first to run this workflow. Once you have donwloaded the workflow file, install it using the 'Import workflow' function within Knime.

You (or your institution) will need a subscription to Factiva to obtain the kind of data that this workflow accepts. Within Factiva, save one page of search results (100 articles) at a time in full text (not headline) format, and in HTML (not PDF or RTF). Be prepared: you will be harrassed by Captcha screens. After 12 pages, these will kick into overdrive and become too much to bear, so the best thing to do is to wait several hours (I suspect it takes at least 4 hours to reset) before you continue the process.

I accept no responsibility whatsoever for what you do with this workflow, especially if it happens to violate Factiva's terms of service.

I also can't guarantee that the workflow will actually do what it is supposed to, since it will break as soon as Factiva changes the format of their HTML outputs. All I can say for sure is that it was working effectively with outputs obtained from Factiva in late February 2019. If and when it does break, I cannot guarantee that I will fix it.

I wrote a blogpost about this workflow at http://seenanotherway.com/facteaser/. It contains jokes.
