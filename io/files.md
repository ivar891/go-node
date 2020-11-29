
write to a file 

fs.writeFileSync('filename','text to write')
fs.appendFileSync()

when you read contents of file it is binar and is represented in 
1)Node as buffer
  converted to string using bufferVariable.toString()
2)bytes in golang
  converted to string using string(bytevalue)
  
  
