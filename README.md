# Docker Networking: Creating, Managing, and Troubleshooting Container Networks
This is the repository for the LinkedIn Learning course Docker Networking: Creating, Managing, and Troubleshooting Container Networks. The full course is available from [LinkedIn Learning][lil-course-url].

![lil-thumbnail-url]

## Course Description

This course introduces the essentials of Docker networking for containerized applications. Instructor Shelley Benhoff explores Docker’s built-in network types and shows how to select the right one for various use cases. Through guided exercises and demonstrations, learn how to create, manage, and secure container networks to support scalable applications. The course covers key skills such as setting up inter-container communication and using Docker’s DNS for simplified connections. Troubleshooting scenarios are included to help diagnose and resolve common networking issues. By the end, you’ll have the knowledge to set up robust Docker networks that improve both security and scalability across your container environments.

_See the readme file in the main branch for updated instructions and information._
## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

## Installing
1. To use these exercise files, you must have the following installed:
	- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
    - [VSCode](https://code.visualstudio.com/download)
2. Clone this repository into your local machine using the terminal (Mac), CMD (Windows), or a GUI tool like SourceTree.
3. Use the included cheatsheet.txt file to copy and paste the commands used in each video into the terminal.

## Instructor

Shelley Benhoff is an author, Docker Captain, and co-owner at HoffsTech, LLC.

Shelley has over 25 years of experience in tech as a developer, trainer, author, and speaker. She has a passion for sharing knowledge to support developer success through content creation, publications, and speaking engagements. As a moderator, Shelley has managed several online developer communities to provide a safe space for developers to discuss their learning process, career goals, and challenges.
                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/shelley-benhoff).


[0]: # (Replace these placeholder URLs with actual course URLs)

[lil-course-url]: https://www.linkedin.com/learning/
[lil-thumbnail-url]: https://media.licdn.com/dms/image/v2/D4D0DAQEK81kagnSqfg/learning-public-crop_675_1200/B4DZVdBE7iG8Ac-/0/1741022318584?e=2147483647&v=beta&t=zkcE-Ysb8KGf9XtvNEBSifD3Nw1Nyn0B43TSyytqoCo

