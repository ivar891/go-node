Writing a Server in Go and Node

Node:

const app = express();

app.set("view engine", "ejs"); app.set("views", "assets/authorization-server"); app.use(timeout); app.use(bodyParser.json()); app.use(bodyParser.urlencoded({ extended: true }));

app.get("/authorize", (req, res) => { //handler code });

const server = app.listen(config.port, "localhost", function() { var host = server.address().address; var port = server.address().port; });

Golang:

http.HandleFunc("/", handlers.RootHandler) 
http.HandleFunc("/winners", handlers.WinnersHandler) 
http.ListenAndServe(":8000", nil)

<b>Get a url query parameter</b>

Go:
req.URL.Query().Get("client_id")

Node
req.query.client_id;


in Node it is 
req,resp
in Go it is 
responseWriter,request
