# SAMT Template

## Workflow
**SAMT Template** is a particular type of GitHub repository that lets you speed up the setup phase and start modeling your APIs immediately.

The general idea is straightforward – to create a new project based on this template, you need to log in to your GitHub account and use the **Use this template** green button.
And remember – **do not fork it!**

Right after the [@actions-user](https://github.com/actions-user) actor pushes the second commit to your repository, you're ready to clone it in Visual Studio Code.

From now, everything's in your hands!

## Content

After you create a new project based on the current template repository using the **Use this template** button, a bare minimal scaffold will appear in your GitHub account with the following structure:

```
.
├── README.md                       README file
├── .samt
│   └── samt-wrapper.properties     SAMT Wrapper configuration
├── samtw                           *nix SAMT Wrapper script
├── samtw.bat                       Windows SAMT Wrapper script
└── src
    ├── greeter.samt                Example greeter API
    ├── greeter-provider.samt       Example greeter provider
    └── greeter-consumer.samt       Example greeter consumer
```

## Getting help

If you're stuck with anything related to this template, check out the following resources:

- [Getting Started](https://github.com/samtkit/core/wiki/Getting-Started)
- [Wiki](https://github.com/samtkit/core/wiki)
- [Template Issue Tracker](https://github.com/samtkit/template/issues)
