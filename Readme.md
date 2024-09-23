# Scala Jupyter Notebook

This project provides a setup to run Scala Jupyter Notebooks in Visual Studio Code (VSCode).

It provides some demos and examples to get you started with Scala programming in Jupyter Notebooks and displaying graphs and visualizations.

## Requirements

To run the Scala Jupyter Notebook on VSCode, you need the following:

1. **VSCode**: Make sure you have the latest version of Visual Studio Code installed. You can download it from [here](https://code.visualstudio.com/).

2. **Jupyter Extension**: Install the Jupyter extension for VSCode. You can find it in the Extensions Marketplace within VSCode or install it from [here](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter).

3. **Scala Language Support**: Install the Metals extension for Scala language support in VSCode. You can find it in the Extensions Marketplace or install it from [here](https://marketplace.visualstudio.com/items?itemName=scalameta.metals).

4. **Almond Kernel**: Install the Almond kernel to run Scala code in Jupyter Notebooks. You can install it with [Coursier](https://get-coursier.io/) using the following commands:

```sh
curl -Lo coursier https://git.io/coursier-cli
chmod +x coursier
./coursier launch --use-bootstrap --fork almond --scala 3.3 -- --install --force --scalafmt --id scala3 --display-name "Scala 3.3"
```

## Setup

1. **Open VSCode**: Launch Visual Studio Code.

2. **Open Folder**: Open the folder containing your Scala Jupyter Notebook project.

3. **Create or Open Notebook**: Create a new Jupyter Notebook file (`.ipynb`) or open an existing one.

4. **Select Kernel**: Select the Almond kernel for Scala from the kernel selection dropdown in the top-right corner of the notebook interface.

5. **Start Coding**: You are now ready to write and execute Scala code in your Jupyter Notebook within VSCode.

## Additional Resources

- [VSCode Documentation](https://code.visualstudio.com/docs)
- [Jupyter Documentation](https://jupyter.org/documentation)
- [Almond Documentation](https://almond.sh/docs/)
- [Dedav4s visualization library](https://quafadas.github.io/dedav4s/)
- [Vega Visualization Library](https://vega.github.io/vega/)

Enjoy coding with Scala in Jupyter Notebooks on VSCode!
