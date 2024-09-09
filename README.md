# AutoDeployToFTP
[AutoDeployToFTP](https://github.com/NoaSecond/AutoDeployToFTP/) is an open-source Continuous Deployment (CD) project designed to automate the deployment of your website to an FTP server.

<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=githubactions"/></a>

## Description
[AutoDeployToFTP](https://github.com/NoaSecond/AutoDeployToFTP/) is a lightweight tool that seamlessly integrates with GitHub Actions. It utilizes YAML (YML) configuration files and establish a connection between your main branch repository to your FTP server who automatically update your code on your FTP server whenever changes are pushed to your repository.

## Setup
To set up [AutoDeployToFTP](https://github.com/NoaSecond/AutoDeployToFTP/) for your project, follow these steps:

### Project Setup
1. Place the `.github` folder at the root of your project.
2. Configure the list of files and folders to `exclude` inside `deploy.yml`.

### Repository Setup
1. On [GitHub](https://github.com/), open your repository.
2. Go to `Settings`.
3. Then drop `Secrets and variables` to open `Actions`.
4. In `Repository secrets`, put the FTP variable to fill `deploy.yml`.
    - FTP_SERVER
    - FTP_USERNAME
    - FTP_PASSWORD
5. Don't forget to click on `Add secret` button below.

That's it! With these simple setup instructions, [AutoDeployToFTP](https://github.com/NoaSecond/AutoDeployToFTP/) will handle the rest, keeping your website FTP server up to date with each commit.

## Contributing
If you would like to contribute to this project, please follow these guidelines:

1. Fork the repository
2. Create a new branch: `git checkout -b my-feature`
3. Make your changes and commit them: `git commit -am 'Add some feature'`
4. Push the branch to your forked repository: `git push origin my-feature`
5. Submit a pull request

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
