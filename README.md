# DB-Chat-Application

**Funktion:**

<p align="center">Display GUI and get User Input:</p>

<p align="center">
  <img src="GUI.png">
</p>

## How to communicate with a DB

**DB Access**

```
MySqlConnection myConnection = new MySqlConnection("SERVER=localhost;DATABASE=XXXX;UID=root;PASSWORD=;");
myConnection.Open();
```

**Connect to DB**

```
myCommand.Connection = myConnection;
```

**Creat SQL Command**

```
string myInsertQuery = "INSERT INTO t_chatquote (timestamp) Values('DateTime.Now.ToString("yyyy-MM-dd HH:mm")')";
MySqlCommand myCommand = new MySqlCommand(myInsertQuery);
```

**Send SQL Command**

```
myCommand.ExecuteNonQuery();
```

**Close DB Access**

```
myConnection.Close();
```

## Where you can find more Stuff about me:

[Sei's Homepage](https://sei-vae.github.io/)
