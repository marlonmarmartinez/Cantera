# Cantera
package cantera;



public class Consultas {
    int cedula=1066737209;
    
     public boolean Consultar_Reservas_Por_Cedula(int ced){
         boolean con=false;  
        if(cedula==ced){
            con= true;
        }
        return con;
    }
    
}

