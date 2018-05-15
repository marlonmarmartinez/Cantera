# Cantera

package cantera;

public class Cantera {

    
    public static void main(String[] args) {
        Consultas con=new Consultas();
        boolean consulta=con.Consultar_Reservas_Por_Cedula(1066737209);
        if(consulta==true){
            System.out.println("accedio correctamente a su consulta de vuelo");
        }else{
            System.out.println("su cedula no tiene reserva, le sugerimos hacer su respectiva reserva");
        }

        
    }
   
}
