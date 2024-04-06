<div align="center">
<a href="https://github.com/NicoFilips/csharp-designpatterns/">
  <img src="https://github.com/NicoFilips/dotnet-pipeline-template/assets/35654361/967a9c31-e83b-42a7-acda-641b14d5142e" alt="Logo" width="200" height="200">
</a>
<blockquote>
  <p>Source: DALL-E 3</p>
</blockquote>

</div>

## About the Repository 📖

This repository is a comprehensive collection of design pattern examples in C#. It's intended for developers looking to deepen their understanding of design patterns and apply them in real-world software development. The patterns covered include Creational, Structural, and Behavioral patterns, providing a wide range of solutions to common software design challenges.

## Features 🚀

To integrate this pipeline into your Tools - create a dotnet.yml in your github/workflows folder and copy this code:
```
name: NicoFilips-template-pipeline(build/test/publish/DeployNuget)

on:
  push:
    branches: 
      - main
  workflow_dispatch:

jobs:
  call-template-workflow:
    uses: NicoFilips/dotnet-pipeline-template/.github/workflows/dotnet-pipeline-template.yml@main
    with:
      publish: true
```
Then you can checkout the pipeline in this repository to use it in your own!

## Support 🆘

If you encounter any issues or have questions, [open an issue](link-to-issues) on our GitHub page.

## Contributing 👥

Contributions are welcome! If you have a design pattern example to add or improvements to suggest, please check out our [Contributing Guidelines](link-to-CONTRIBUTING.md).

## License 📄

This repository is released under the [MIT License](link-to-LICENSE).
