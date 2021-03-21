# gdrivemirror-workflow

To build your own GDrive Mirror Bot you can use [This REPO](https://github.com/lzzy12/python-aria-mirror-bot) as a template.

## How To Use WorkFlow ???

- First setup everything for your Mirror Bot then push to your private git repository.
- Next, fork [this workflow repo](https://github.com/shn999/gdrivemirror-workflow) to RUN your Mirror Bot.
- Now, Setup your secrets in Settings --> Secrets.
- And create six New Repository Secrets there.

```text
GH_TOKEN
MIRROR_REPOSLUG
GitHubName
GitHubMail
Docker_Username
Docker_Password
```

Here,
- {Name = Value}
- **GH_TOKEN** = Your [GitHub personal access Token](https://github.com/settings/tokens) (for workflow)
- **MIRROR_REPOSLUG** = Your secret Repository, as in "username/reponame"
- **GitHubName** = Your GitHub Username
- **GitHubMail** = Your GitHub Email address
- **Docker_Username** = Your [DockerHub](https://hub.docker.com) Username
- **Docker_Password** = Your [DockerHub](https://hub.docker.com) Password

That's all.

Finally, go to Actions tab and Run the Workflow 😜


# Notes 

This is only for debugging purpose. If you use it for deploying your account you might get Ban. We are not responsible for any action taken by GitHub.


# Credits

[rokibhasansagar](https://t.me/fr3akyphantom) , [henloboi](https://t.me/henloboi) , [ElytrA8](https://t.me/ElytrA8) for help & repo.
