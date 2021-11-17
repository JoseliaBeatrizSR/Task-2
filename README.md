 let tabela = "create table author (id number, name string, age number, city string, state string, country string)";
let tableName = tabela.substr(12,7);
//console.log(tableName);

let columns = tabela.substr(19);
columns = columns.replace(/[()]/g, ' ');
columns = columns.split(',');

//columns=JSON.stringify(columns);

for(value of columns){
   
}

let database = {
  tables: {
    [tableName]:{
      [columns]:{
  
      },
      data:[],
    },
  },
}
console.log(database)
