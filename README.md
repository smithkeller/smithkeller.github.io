# Smith and Keller Website

## Adding New Clients

### Prerequisites
You'll need all the information for the new company, including a company image/logo.

### 1. Upload company logo.
- Navigate to `/images/clients` folder and select “Upload Files”
- Select “choose your files” and upload the company’s logo that you had saved on your computer.

### 2. Copy profile template and create new page.
- Navigate to `/profiles/template.html` and copy the contents of the file.

IMAGE

> NOTE: Ensure line numbers aren't included in what you copy.  You just want the code.  If it's easier you can view the "Raw" format and copy it from there.

- Once you have the contents of `template.html` copied, navigate back to the `/profiles` folder and select "Create new file".

IMAGE

- Title the file with the company name (ie. companyname.html) and paste the text you copied from the `template.html` into the content section.

IMAGE

- Update the content with the necessary company information.

- Scroll to the bottom of the page and select "Commit new file".  Leave the "Commit directly to the `master` branch." option selected.


### 3. Add company to alphabetized directory page.

- Once you've created the company profile page, you just need to add the company to the directory.  Navigate to the `directory.html` file at the root of the project and click the pencil at the top right to edit the file.

- Copy lines 39 - 51.  This is the section for a company profile in the directory.

- Find where the company your adding fits into the list of clients alphabetically, and paste what you copied from line 39 - 51 there.

- Update the information you pasted with the correct information for the new company.  Make sure the `<a href="profiles/crediblehealth.html">` section that you copied is update with the new html file you created in the previous step.  It should look like `<a href="profiles/companyname.html">`.

- Scroll to the bottom of the page and select "Commit new file".  Leave the "Commit directly to the `master` branch." option selected.

### 4. Verify changes.
- The changes should take affect immediately, however sometimes your browser caches previous versions.  Make sure you refresh the page a few times if it appears the changes didn't take affect.
