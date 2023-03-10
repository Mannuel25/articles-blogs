Contributing to the Cybersecurity Blog Posts
============================================

This repository has been created to store copies of all articles posted on the main cybersecurity website. This allows us to have a backup of all articles published, and provides a great first issue concept for those beginning on their GitHub journey.

**What will this contribution require:**

Getting involved in this repository is primarily aimed at those just starting out on their GitHub journey. It will present a great opportunity to learn the basics of using GitHub, and understanding core concepts. It will also allow you to open up certain GitHub achievement badges on your profile.

**Example steps for contribution:**

* Visit the TODO.md page
* Choose an article to copy across
* Visit the main cybersecurity blog
* Copy content of chosen article into this repository

**Warning: non-trivial pull requests (anything such as fixing a typo)
will be closed!** `Please create an issue` to suggest such changes.

[Create New Issue](https://github.com/ProfCyberNaught/cybersecurity-blog-posts/issues "Create New Issue")

Cybersecurity Blog Posts uses GitHub to keep track of bugs, feature requests, and associated
patches because GitHub now provides enough adequate tooling for its community.
Patches can be submitted as pull requests, but if you don't create an issue,
it's unlikely that we'll notice your contribution or accept it. Please make sure you
document your contributions well enough for us to understand the changes.

Contributing to the Cybersecurity Project
=========================================

If you wish to get involved in this project and copy over one of the articles from the main cybersecurity blog, you must follow the below steps to complete the process.

We have implemented a **blank_article_layout_template.md** file stored in the main repository directory. You can view the file, add the required data, then update the main README.md and TODO.md tables to reflect changes made. Then submit a pull request.

**Please follow the below steps to contribute:**
<br /><br />

#### FOLK THIS REPOSITORY & CREATE NEW BRANCH

**STEP 1:**

- Comment on the `MAKE AN ARTICLE COPY` issue
    - Add a comment stating which article you would like to attempt
        - We may comment on your issue to confirm
        - We may give alternative instructions or a different article
        - Please check your notifications regarding the issue

**STEP 2:**

- Create a folk of this repository
    - Confirm `contribute to parent project` setting

**STEP 3:**

- Fetch the repository to your local machine

**STEP 4:**

- Create new branch called: `NewArticleBackupPage`
    - **Notice:** We will not accept commits from `master` or other named branches

**STEP 5:**

- Switch to the new branch name `NewArticleBackupPage` 
<br />

#### CHOOSING AN ARTICLE

**STEP 1:**

- Check the [TODO.md](# "Remaining Articles to Copy") file 
    - Choose article you wish to copy
        - Check the `issue comments` section
            - Make sure nobody else has started to copy this article
        - View the article on the main blog `click the link`

**STEP 2:**

- Add a comment to the issue 
    - Let people know you are going to copy an article 
    - Provide the article title in your comment 
<br />

#### USING THE BLANK ARTICLE TEMPLATE FILE

**STEP 1:**

- Copy the `blank_article_layout_template.md` file into the `pcn_cybersecurity_articles` directory 
- Rename this file with the name of your chosen article with a `.md` at the end
    - File name must only consist of:
        - lowercase letters, numbers, and hypens
        - Spaces must be replaced with a hyphen `-`
        - No other additional characters must be used
            - Example: `my-article-name.md`

**STEP 2:**

- Edit the template file 
    - Read the instructions within the blank template file `has been commented`
    - Replace `variable codes` with the required article data
        - If you need more detailed instructions, view the `COPY_ARTICLE_DETAILED_INSTRUCTIONS.md` file
    - Save changes

**STEP 3:**

- Confirm your additional new file created 
    - Commit your changes to `NewArticleBackupPage` 
        - Use commit title: `Create <filename>`
            - Replace `<filename>` with your new file
            - (example: `new-article-name.md`) 
        - Use commit description: `Copied a new article over from the main website` 
- Commit changes to `NewArticleBackupPage`
<br />

#### UPDATE README.md FILE

**STEP 1:**

- Open the `README.md` file from the main directory
    - Add additional table row in section `A List of Cybersecurity Blog Posts in this Repository`
        - Copy template table row from commented section
            - Must include four columns
                - `article title`, `main article link`, `GitHub article link`, `your GitHub link`
            - Must include the `<!-- Divider -->` comment at the end
        - Paste new row at the bottom of the table
            - New row must not have extra line breaks between other rows
                - This will break the layout if you do
        - Populate the `variable codes` with the required information
            - Refer to existing rows for further clarity
    - Save changes

**STEP 2:**

- Confirm your updates made 
    - Commit your changes to `NewArticleBackupPage` 
        - Use commit title: `Updated README.md`
        - Use commit description: `Updated the README.md file to add newly copied article` 
- Commit changes to `NewArticleBackupPage`
<br />

#### UPDATE TODO.md FILE

**STEP 1:**

- Open the `TODO.md` file from the main directory
    - Locate your chosen article title
        - Change status column of the article title:
            - If states `Completed`:
                - You have copied an article that has already been done
                    - Your contribution will be rejected
                    - Please copy a different article
            - If states `Not Copied`:
                - Change text `Not Copied` to `Completed`
    - Save changes

**STEP 2:**

- Confirm your updates made 
    - Commit your changes to `NewArticleBackupPage` 
        - Use commit title: `Updated TODO.md`
        - Use commit description: `Updated the TODO.md file to change status of newly copied article` 
- Commit changes to `NewArticleBackupPage`
<br />

#### FINAL CONTRIBUTION STEPS

**STEP 1:**

- Push your commit to your repository folk

**STEP 2:**

- Create Pull Request
    - Populate pull request with required data
        - Complete the `checklist`:
            - Remove the space between `[]` and add an `x` for each step completed
            - (example: `[x] (required)`) 
        - Leave the `Required and not optional` checked
            - You are required to agree to these conditions
            - If you do not, your contribution will be rejected
        - Add article title in section
        - Replace `[ARTICLE-TITLE]` with article title
        - replace `[ARTICLE-URL]` with main article URL
        - Add the date you copied the article
        - Add any issues you experienced (if any)
        - Add any further changes required (if any)
        - Add any additional documentation ideas (if any)
        - Add any other information you feel is needed (if any)
    - Submit your `pull request`
<br />

**NEXT STEPS**

Now you can sit back and wait for us to `review` your pull request submission. If we find issues with your submission, we will `request changes` on your pull. If we are satisfied with your request, we will `merge` your new branch `your-github-profile-name/cybersecurity-blog-posts/NewArticleBackupPage` with our `ProfCyberNaught/cybersecurity-blog-posts/main` branch.

We always leave reviews and comments for all our pull requests. Thank you for volunteering your time to copy over a main article and submitting the required data as detailed above.

**Support**

If you need support whilst you are creating your new copied article data, or following the detailed steps provided above, please `leave a comment on your issue`. We will try advise as much as we can to allow you to successfully complete your pull request.


Code of Conduct
===============

As a `contributor`, you can help us keep our community open and inclusive.
Please read and follow our [Code of Conduct](./code_of_conduct.md "Code of Conduct - Cybersecurity Blog Posts") 