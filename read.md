------------------------------------------------------------
for different config.js file name 
 "build":"webpack --config custom.js" 

for change entry and output(exit file)

----------------------------------------------------------------------

const path=require("path");
module.exports={
    mode:"development",
    entry:'./src/App.js',
    output:{
        path:path.resolve(__dirname,'dist'),
        filename:"output.js"
    }
}