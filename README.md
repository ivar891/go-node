# go-node
Develop Go and Node 

go version

node -v

nodejs is a chrome v8 java script runtime written in cpp
node sends javascript code to v8 engine alaong with some cpp bindings for methods that are not in javascript spec like fs.readFile,os.platform etc, v8 engine executes and sends results back to node

node doesnt know how to run js , it delegates to v8 engine 
v8 doesnt knwo how to interact with dom or file system chrome/node provide bindings for it

node: global,process [process.exit()]
chrome: window,document

console.log is node/chrome api not java script


In Go we dont need () for if 
In Node we need ()


typeof
reflect.TypeOf()

CHECK IF ALL STRINGS IN ARG2 ARE IN ARG1
containsAll(client.scopes, scope.split(" "))


randomString()

delete a key from map
delete requests[requestID]
delete(requests,requestID)
