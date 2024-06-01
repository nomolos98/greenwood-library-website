# Capstone Project: Greenwood library website maintenace

### Background Scenario

Development team tasked with enhancing the website for the "Greenwood Community Library." The website aims to be more engaging and informative for its visitors. It currently includes basic sections: Home, About Us, Events, and Contact Us. Your team decides to add a "Book Reviews" section and update the "Events" page to feature upcoming community events.

Simulate the roles of two contributors: "Morgan" and "Jamie". Morgan will focus on adding the "Book Reviews" section, while Jamie will update the "Events" page with new community events.

### Objectives
- Practice cloning a repository and working with branches in Git.
- Gain experience in staging, committing, and pushing changes from both developers.
- Create pull requests and merge them after resolving any potential conflicts.

### Setup

To set up the project locally

Create a Repository on GitHub:

Name it greenwood-library-website.

Initialize it with a README.md file and clone it to your local machine.

**Tasks**

1. Navigate to the local project directory:
    ```bash
    cd Documents/Darey.io/capstone-project
2. Clone the repository:
    ```bash
    git clone https://github.com/nomolos98/greenwood-library-website.git
    ```
3. In the main branch, using the Visual Studio Code editor, ensure there are files for each of the web pages.
- home.html
- about_us.html
- events.html
- contact_us.html

4. Stage, commit, and push the changes
```bash
git add *
git commit -m "Initialised existing code base of the website"
git push origin main
```
### Morgan's Work: Adding Book Reviews
1. Create a branch for Morgan
```bash
git checkout -b add-book-reviews
```
2. Add a new file book_reviews.html to represent the Book Reviews Section:
```bash
<html>
<body>
<title>Book Reviews</title>
<h1>Book Reviews</h1>
<p> 
TEEN BOOK REVIEWS<br>
Teens in grades six through twelve can earn community service by reading books and submitting a review, which will be posted on our website.<br>    
GUIDELINES<br>
You must be in grades 6-12 to submit a review.<br>
Teens can review one book per month.<br>
Each review will be worth 2 community service hours.

</p>
</body>
</html>
```
3. Stage, commit, and push changes:
```bash
git add book_reviews.html
git commit -m "Add book reviews section"
git push origin add-book-reviews
```

4. Raise a PR for Morgan's work:
```bash
# Navigate to your repository on GitHub.
# Click on the "Pull requests" tab.
# Click on the "New pull request" button.
# Select "compare: add-book-reviews" against "base: main".
# Click on "Create pull request".
# Provide a title and description for the pull request (e.g., "Add book reviews section").
# Click "Create pull request".
```
5. Merge Morgan's work into the main branch:

```bash
# Navigate to the "Pull requests" tab in the repository.
# Click on the PR titled "Add book reviews section".
Review the changes. # Optionally, request reviews from team members.
# Once satisfied, click the "Merge pull request" button.
#Confirm the merge by clicking "Confirm merge".
```
### Jamie's Work: Updating Events Page
1. Create a branch for Jamie
```bash
git checkout -b update-events
```
2. Add a new file book_reviews.html to represent the Book Reviews Section
```bash
<html>
<body>
<title>Events</title>
<h1>News & Events</h1>
<p>
Children Day<br>
DATE: May 27 11:00 PM<br>
LOCATION:Civic Centre polo club
</p>
</p>
Democracy Day<br>
DATE: May 29 10:00 AM<br>
LOCATION:Eagle Square Abuja
</p>
</body>
</html>
```
3. Stage, commit, and push changes
```bash
git add events.html
git commit -m "Update events page with latest new events"
git push origin update-events
```
4. Pull the latest changes from the main branch into update-events
```bash
git pull origin main
```
5. Resolve any conflicts if they arise, then push for the final changes.
```bash
git push origin update-events
```
6. Raise a PR for Jamie's work

- Navigate to your repository on GitHub.
- Click on the "Pull Requests" tab.
- Click on the "New pull request" button.
- Select "compare: update-events" against "base: main".
- Click on "Create pull request.".
- Provide a title and description for the pull request (e.g., "Update events page with new community events").
- Click "Create pull request".

7. Merge Jamie's work into the main branch

- Navigate to the "Pull requests" tab in the repository.
- Click on the PR titled "Update events page with new community events".
- Review the changes. Optionally, request reviews from team members.
- Once satisfied, click the "Merge pull request" button.
- Confirm the merge by clicking "Confirm merge".