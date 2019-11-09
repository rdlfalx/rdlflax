# rdlflax
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package number1;

/**
 *
 * @author Rudolf
 */
import java.util.ArrayList;
public class Number1 {

   public static void main (String[] args){
  
   String name, address;
   int age;
   String[] hobbies = {"Sports", "Music", "Movies"};
   boolean b1, b2;
   ArrayList<String>School=new ArrayList<>();
   ArrayList<String>Skill=new ArrayList<>();
   
   
   name = "Rudolf Alexander";
   address = "Jl.Otista 82 rt.03/rw.06 no.17";
   age = 24;
   b1 = true;
   b2 = false;
   School.add("SD.Antonius 2001-2007");
   School.add("SMP.Marsudirini 2007-2010");
   School.add("SMKN 5 2010-2013");
   School.add("Gunadarma University 2014-2019");
   Skill.add("Java begginer");
   
   String [] arraySchool = new String [School.size()];
   School.toArray(arraySchool);
   for(String schoolTemp: arraySchool){
       
   String [] arraySkill = new String [Skill.size()];
   Skill.toArray(arraySkill);
   for(String skillTemp: arraySkill){

   System.out.println("name = "+ name);
   System.out.println("address = "  + address);
   System.out.println("age = " + age);
   System.out.println(hobbies[1]);
   System.out.println("married = " + b2);
   System.out.println(schoolTemp + ",");
   System.out.println(skillTemp + ",");
   System.out.println("Interest_in_codding = " + b1);
   }
  
   }
  
   
   }
   
   
}
    

