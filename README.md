# bigsilly: Language Support for BigC

- `Ctrl+/`or `Cmd+/` to toggle comments 
- Basic syntax highlighting so that you dont hurt your eyes
- Supports vcode 1.74.0 and higher (if it don't work for you, contact @lanphgphm of this team)

it's silly. don't expect too much. 

this extension must be compiled and installed manually, because to publish it as a public extension, money must be spent, and there is none to be. 

## Installation guide 
1. Clone this repository    
```
git clone https://github.com/GoBigC/bigsilly.git
cd bigsilly
```

2. To try extension before installing   
- Open the bigsilly directory with vscode 
- Press F5, a new vscode window will pop up
- In the new vscode instance, create or open any file with `.uia` extension, you should be able to toggle comment and see basic syntax highlighting 

3. The extension is already built, you dont have to build again, but in case you want to, run   
```
vsce package 
```

4. To install the extension on your vscode  
- Go to Extensions view 
- Click `...` at the top 
- Select "Install from VSIX" 
- Navigate to this directory & choose `bigsilly-0.0.1.vsix`

And enjoy the new extension!