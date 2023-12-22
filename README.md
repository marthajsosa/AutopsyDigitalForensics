# AutopsyDigitalForensics

<h2>Description</h2>
In a Windows 10 virtual machine, used Autopsy forensic platform to investigate an image for evidence pointing to unauthorized access to proprietary company informatin. 
<br />

<h2>Environments Used </h2>

- <b>Windows 10 Virtual Machine</b>
- <b>Autopsy</b>

<h2>Program walk-through:</h2>

<p align="center">
In Windows 10 virtual machine double click on Autopsy icon: <br/>
  <img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/a2a81536-4e2c-4393-b20f-93f602a27587"/>
<br />
<br />
I created a new case in Autopsy by selecting “new case” on the application start up window.  <br/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/377071aa-2e33-4be6-b1be-a46636bbac88"/>
<br />
<br />
On the next screen I entered the case name JSmith_Q1 and set the base directory as C:\Users\LabUser\Desktop\Evidence Files.  <br/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/2f6488b2-7686-4084-adef-7f47a2ac2342"/>
<br />
<br />
On the next screen, I entered the case number as 383070861 and examiner name 383070861 for the case, and then clicked finish. <br/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/1e361bb2-ce26-47f6-8e95-68074efa3f15"/>
<br />
<br />
Next, I selected host, kept the default values, and clicked next.  <br/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/951fb4f0-1b05-4779-a12f-6935555af04e"/>
<br />
<br />
Selected VM File as the data source, and then clicked next. <br/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/1712d392-68f1-489a-8844-2a4cf17d794d"/>
<br />
<br />
I browse to C:\Users\LabUsers\Desktop\EvidenceFiles\JSmith_Q1.001 to select the image file.  <br/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/e4e48026-d2b4-40e8-9382-098744544bf3"/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/23377a55-e5d7-4bbf-84c9-97781f05c8ad"/>
<br />
<br />
Accept the default settings for Configure Ingest and click Next. <br/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/27929c84-85ea-4fa5-976f-56a0ba4c9cd8"/>
<br />
<br />
Once the file has been added to the database, click finish. <br/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/6a0dec13-c01b-4f98-80a3-c6264e0e08e5"/>
<br />
<br />
Now, it is time for my own discovery and analysis. As I looked through the image of Mr. Smith’s device, I exported relevant findings to an evidence folder. First, I took time to familiarize myself with the left pane of the Autopsy window, noted how the data is organized in a tree/branch structure. <br/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/34996f9a-2338-45c1-92ab-a1555aee9a12"/>
<br />
<br />
After expanding the branches under File Types, I noticed 379 image files.  <br/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/ec3e1f89-376d-4624-9bff-048c8bcd30b4"/>
<br />
<br />
I glanced through the Metadata branch and took note of some interesting file names. I wondered if these files could be found.  <br/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/51e9dc8d-4782-4459-ad66-8ac8e6073224"/>
<br />
<br />
And then found those same files in the deleted files branch. These files were all exported to the evidence folder for further inspection. <br/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/9b5dbad7-f77c-4f6f-be16-6682371e309b"/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/e54e4dec-0e90-4d01-afc1-66e4e8f822c6"/>
<br />
<br />
Several images showing what could be company trade secrets. We know Mr. Smith does not have authorization to have any proprietary information. I noted mentions of Bitcoin. <br/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/29ad6ed3-e19b-411d-a5f3-c7e4904b0564"/>
<br />
<br />
Several images that suggest an interest to trade data for payment, as well as more company secrets. <br/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/b510a19a-c579-47c6-8269-292688d4f9b8"/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/a56c7132-352f-474f-a103-ff25e25f573d"/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/396ed77e-06d5-4b68-82bf-a5cc68797809"/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/1f498cdb-1312-4ac5-9042-046e71605fd3"/>
<br />
<br />
Keyword search for the words “confidential” and "restricted" led to many of the same results that were in the deleted files branch. <br/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/4124d83e-4613-4173-93ac-37ba30d4be1c"/>
<img src="https://github.com/marthajsosa/AutopsyDigitalForensics/assets/146014829/e84290c7-50af-4a4e-ab6c-ea66db8100bb"/>
<br />
<br />
An abundance of evidence connecting John Smith to unauthorized access to proprietary company information. Mr. Smith is not authorized to access any proprietary information whatsoever; however the image of his device contains several deleted documents and images containing those very things which prove a policy violation on the part of Mr. Smith. Further, there are several pieces of evidence pointing to Mr. Smith’s research on Bitcoin, Bitcoin transactions, and how to complete Bitcoin transactions anonymously. This may be enough to prove an intent to sell company secrets in exchange for money. <br/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
