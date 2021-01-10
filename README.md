# Get-Key-value-from-jsObject

You can get specific key values from a JavaScript object.
  
## Usage
      
      getkeyVal(object,key,callback)
    
  var obj = {
            firstName:'John',
            lastName:'Smith',
            address:'US'
        }   
        
      getkeyVal(obj,'lastName')//output => Smith
            or
      getkeyVal(obj,'lastName',function(value){
           console.log(value)  //output => Smith
        })
        
        
      getkeyVal(obj,['firstName','lastName'])//output => ["John", "Smith"]
           or
      getkeyVal(obj,['firstName','lastName'],function(values){
           console.log(values)  //output = > ["John", "Smith"]
      })
      
      
   var obj2 = [
          {
                firstName:'John',
                lastName:'Smith',
                address:'US'
           }
        ]
   
       getkeyVal(obj2,'firstName')//output => John

      


        
     
     
