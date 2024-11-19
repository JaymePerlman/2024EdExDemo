Importing a repository with GitHub Importer
If you have a project hosted on another Git-based hosting service, you can quickly import it to GitHub using the GitHub Importer tool.

In this article
About repository imports with GitHub Importer
Importing a repository with GitHub Importer
About repository imports with GitHub Importer
GitHub Importer imports the source code and commit history of Git repositories hosted on external hosting services. For more information about the capabilities and limitations of GitHub Importer, see "About GitHub Importer."

GitHub uses the email address in the commit header to link a commit to a GitHub user. To correctly attribute commits in an imported repository, users will need to add the email address associated with their commits to their account on GitHub. For more information, see "Adding an email address to your GitHub account."

Importing a repository with GitHub Importer
When you import a repository using the GitHub Importer, a new repository will be created. If you already have an existing repository you want to use, you can instead add your local repository to GitHub using Git. For more information, see "Adding locally hosted code to GitHub."

In the upper-right corner of any page on GitHub.com, click , and then click Import repository.

Screenshot of the top-right corner of any page on GitHub. A plus icon is highlighted with an orange outline.
On the "Import your project to GitHub" page, enter the URL for the remote repository hosted on another platform.

If the source repository is private, enter credentials for authentication. GitHub Importer will use the credentials to perform a git clone operation on the source repository.

Choose an owner and a name for the new repository on GitHub.

Choose the visibility of the new repository. For more information, see "About repositories."

Click Begin import.

You'll be redirected to a "Preparing your new repository" page, where you can track the status of your import. You'll receive an email when the repository has been completely imported.

