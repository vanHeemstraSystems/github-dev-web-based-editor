# 200 - Codespaces and the web-based editor

Both the web-based editor and GitHub Codespaces allow you to edit your code straight from your repository. However, both have slightly different benefits, depending on your use case.

| | web-based editor | GitHub Codespaces |
| -- | -- | -- |
| Cost | Free. | Costs for compute and storage. For information on pricing, see "About billing for GitHub Codespaces." |
| Availability | Available to everyone on GitHub.com. | Available for organizations using GitHub Team or GitHub Enterprise Cloud. |
| Start up | The web-based editor opens instantly with a key-press and you can start using it right away, without having to wait for additional configuration or installation. | When you create or resume a codespace, the codespace is assigned a VM and the container is configured based on the contents of a ```devcontainer.json``` file. This set up may take a few minutes to create the environment. For more information, see "[Creating a Codespace](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace)." |
| Compute | There is no associated compute, so you won’t be able to build and run your code or use the integrated terminal. | With GitHub Codespaces, you get the power of dedicated VM on which you can run and debug your application. |
| Terminal access | None. | GitHub Codespaces provides a common set of tools by default, meaning that you can use the Terminal exactly as you would in your local environment. |
| Extensions | Only a subset of extensions that can run in the web will appear in the Extensions View and can be installed. For more information, see "[Using extensions](https://docs.github.com/en/codespaces/the-githubdev-web-based-editor#using-extensions)." | With GitHub Codespaces, you can use most extensions from the Visual Studio Code Marketplace. |

# 300 - Continue working on Codespaces

You can start your workflow in the web-based editor and continue working on a codespace, provided you have [access to GitHub Codespaces](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace#access-to-codespaces). If you try to access the Run and Debug View or the Terminal, you'll be notified that they are not available in the web-based editor.

To continue your work in a codespace, click **Continue Working on…*** and select **Create New Codespace** to create a codespace on your current branch. Before you choose this option, you must commit any changes.

![codespaces-continue-working](https://user-images.githubusercontent.com/1499433/200342170-e2e1b467-e272-4b36-8ba8-e8d1593a3026.png)