# Semana_4
Repo para la semana 4 de progra

Maateria de clase

progrmacion orientada a objetos, la idea de esto es ver todo como un objeto 
es un paradigma de programacion que pretende identificar todo como si fuese un objeto, ( todo es un objeto, sea tangible o no)

ejemplo como un carro por ejemploL:
    se desplaza, se parquea, transporta.

( para determinar un objeto es necesario estudiarlo)

es importante crear un diagrama para lleavar el control ( imgagenes con rayas que identifican un problema o situacion)

para identificarki en neatbeans se ve en (project files) dentro del cafe


/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Main.java to edit this template
 */
package javaapplication3;

/**
 *
 * @author LABORATORIO 04
 */
public class JavaApplication3 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        
        calculadora calc = new calculadora();
        System.err.println("la suma de  5 + 4 es:" + calc.sunaDosNumeros(5, 4));
    }
    
}
______________________________________


/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package javaapplication3;

/**
 *
 * @author LABORATORIO 04
 */
public class calculadora {
    
    public double sunaDosNumeros (double a, double b){
        return a + b;
        }
    public double restaDosNumeros (double a, double b){
        return a - b;
        }
     public double divideDosNumeros (double a, double b){
        return a / b;
        }
    public double multipicaDosNumeros (double a, double b){
        return a * b;
        }
}


