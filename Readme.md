# How to detect that the new page is being created in the BeforePrint event handler


<p>Note: This example uses undocumented behavior of the XtraReports Suite, so we cannot guarantee that it will work correctly in the XtraReports Suite.</p><p>This example illustrates how to detect that a new page is being created and obtain the current page number within the BeforePrint event handler via the PrintingSystem.Document.PageCount property. Note that in this scenario, you should set the DetailBand.KeepTogether property to true.</p><p>Another (and more universal) approach to this task is demonstrated at <a href="https://www.devexpress.com/Support/Center/p/E1952">E1952</a>.</p><p>See also: <a href="https://www.devexpress.com/Support/Center/p/AS16487">AS16487</a>.</p>

<br/>

