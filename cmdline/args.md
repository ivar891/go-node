

node app.js add --title="this is a title"

process.argv[2]

process.argv is a raw version

we can use yargs for parsing ,which gives us the name of file in $0 ,array of args and ,parsed args as map 
in the above line we can extract title 
$0 is app.js
and array has add value

vs process.argv has <i>title=this is a title</i> as array element

yargs also has default support for versioning, default is 1,0.0 but can be custpomized using

yargs.version('1.3.0')


yargs.command({
  command: "add",
  describe: "add a new note",
  builder: {
    title: {
      describe: "titel for nmote",
      demandOption: true,
      type: "string"
    },
    body: {
      describe: "body of note",
      demandOption: true,
      type: "string"
    }
  },
  handler: function(argv) {
    console.log("Adding a new nodte", argv.title, argv.body);
  }
});

demandOption makes the argument required
type disables default type inferring and uses the type specified

===

go

