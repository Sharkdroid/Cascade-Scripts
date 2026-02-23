## Sitemap Script

### Description
This script takes a CSV as input. The CSV contains the assets that have sitemap metadata of "No" and sets it to "Yes".<br>
***note**: This script is for site www.csi.edu only*

> **Generating CSV**
> - Navigate to /_common/_cms/formats/_dev/_dev-sitemap-csv
> - Edit the format
> - Under `Preview Options`<br>
>     - **Select an asset type**: Block & context page
>     - **Context block**: /_common/_cms/blocks/_dev/all-pages-sitewide
>     - Leave the page blank <br>
> - Click `Test Format`
> - Copy & paste output into a new file inside the working directory with a `.csv` extension
3. Rename [.env.example](.env.example) to `.env` and fill in the required values.
    - [Where to get API Key?](https://github.com/Sharkdroid/Cascade-Scripts/tree/base?tab=readme-ov-file#getting-api-key-in-cascade)
4. Open the `.csv` you created, Rainbow CSV should auto-detect file extension
5. Go to the bottom of the VSCode look for a button named 'align' click it once
6. It should change to 'shrink' click it again *(this removes tabs and inconsistant formatting)*
7. Run the program!
    - *common error while running the program the Cascade format may generate extra fields this program will detect these and notify the user which path to correct*
    - Results will be generated as a `.log` file


