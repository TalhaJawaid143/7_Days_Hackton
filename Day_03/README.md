Day 3: API Integration and Migration:

Day 3 was all about integrating APIs and migrating data to set up my e-commerce project. 🛠 I started by creating a new project on Sanity and followed their setup process. After running the command provided by Sanity in the terminal, I generated an API token and securely added it to the ".env file" as" SANITY_API_TOKEN".
Next, I created a scripts folder and added a file named "importSanityData.mjs". I also worked on "schema types" by creating a "product.ts" file within the schemaTypes folder. Along the way, I encountered some errors in "importSanityData.mjs", but Alhamdulillah, I was able to resolve them.
I then added my project "ID" and "token" from Sanity to the "index.ts" file and updated the "package.json" file by adding a new script:
"import-data": "node scripts/importSanityData.mjs"

After running "npm run data-import" to check the data, I initially didn’t see the expected results. To fix this, I ran the "npm install data-fetch" command, which resolved the issue. Finally, I could see the product details both in my project and on the Sanity Studio dashboard. 🎉
