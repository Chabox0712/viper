# Viper v3.2.5

## What is This Project?

This project has been created as an open-source alternative to tool called **Viper-v3.2.5**. This project has been created after the owners actions towards community. The project is a complete rewrite of the original project and is not based on any of the original code.

## What is Viper?

Viper is a hacking shell tool for game named Grey Hack. It is used to automate some of the tasks that are done manually. It is also used to make the game more fun and easier to play.

## How to Install?

You can build this project from source or download the pre-built binaries from the www.viper.net website(in game).

## Building the Tool

#### Setting Up Your Workspace

1. Clone the repository to your local machine using Git:
   ```
   git clone https://github.com/Chabox0712/viper.git
   ```
2. Open the cloned project in Visual Studio Code to set up your workspace.
3. Download Greybel VS extension from Visual Studio Code Marketplace.

#### Compiling the Code
1. Navigate to greybel extension settings `@ext:ayecue.greybel-vs` and change `Ingame Directory` to `/viper/`
2. Navigate to the `main.src` file within VS Code.
3. Right-click on `main.src` and select the `Build` option from the context menu. Successful compilation will create a new `build` directory in your project.
4. Copy `viperSetup.src` to the game, compile and run it in the game and copy everything in the `build` folder in `vscode` to greyhack
`/viper/` folder accordingly.
4. To deploy the tool in Grey Hack, copy the `installerX.src` files from the `build` folder into the game. Alternatively, you can automate this step by configuring the `Greybel › Create Ingame` setting in the Greybel VS extension.

#### Integrating with Grey Hack

1. Within Grey Hack, build and run each `installerX.src` file.
2. Change your directory to `/viper/` using the command:
   > [!Note]
   > The installation directory for the installers can be customized in the Greybel VS extension settings.
3. Compile the main script to your preferred location in the game with:
   ```
   build main.gs <YourTargetDirectory>
   ```
4. After installation, you may optionally remove all files generated by the installers as they are no longer necessary.

## Contributing

If you want to contribute to this project, you can do so by creating a pull request. You can also create an issue if you find any bugs or want to suggest a feature.

Please subscribe to my  YOUTUBE channel at [chabox](https//youtube.com/@chaboxgaming)

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.
