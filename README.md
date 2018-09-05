# OchoLoco
OchoLoco Cartas
////////////////////Carta.java///////////////////////
/* Caso de estudio: Ocho loco
 * Repaso del encoque orientado a objetos
 * Taller1
 * Curso de PI
 * EISC Univalle
 * Juan Felipe Alvarado(1745283)
 * Daniel Bermudez (1742658)
 
 */

package ochoLoco;

import java.util.Random;
import java.util.ArrayList;

public class Carta {
	/*
	 * ArrayList<String> nombreArrayList = new ArrayList<String>();
	 * 
	 * 
	 */
	
	public Carta()
	{
		
	}
	
	String[] Palo = {"P", "C", "T", "D"};
	
	String[] Numero = {"A", "2", "3", "4", "5", "6", "7", "8", "9", "10", "J", "Q", "K"};
	
	ArrayList<String> baraja = new ArrayList<String>();
	
	private char palo;
	
	private int numero;
	
	private boolean estado;
	
	private String cartaEnJuego;
	
	public char getPalo()
	{
		return palo;
	}
	
	public int getNumero()
	{
		return numero;
	}
	public boolean getEstado()
	{
		return estado;
	}
	String palos="";
	String numeros="";
	public void cartaRandom()
	{
		for(int palo=0; palo<=3; palo++)
		{
			if (palo==0)
			{
				palos="D";
			}
			else 
				if (palo==1)
				{
					palos="T";
				}
				else 
					if (palo==2)
					{
						palos="C";
					}
				else 
					if (palo==3)
					{
						palos="P";
					}
			for(int numero=1; numero<=13; numero++)
			{
				numeros=String.valueOf(numero);
				if (numero==1)
				{
					baraja.add(palos+"A");
				}
				else
					if (numero==10)
					{
						baraja.add(palos+"Q")
					}
			}
		}
	}
/*	public void cartaRandom()
	{
		Random randomPrincipal = new Random();
		int paloRandom = randomPrincipal.nextInt(3);
		int numeroRandom= randomPrincipal.nextInt(12);
		String cartaEnJuego = Palo[paloRandom] + Numero[numeroRandom];
		//return Numero[numeroRandom] + " de " + Palo[paloRandom];
	}
*/
	
	public boolean cartaRepetida()
	{
		if(retornarRandom==cartaEnJuego)
		{
			
		}
	}
	
	public void repartirCartas()
	{
		for(int i=0; i<=7; i++)
		{
			baraja.add()
		}
	}
	
	

}
//////////////////////COntrol.java///////////////////////

package ochoLoco;
import java.util.Random;

public class Control {
	public String carta()
	{
		
		return " ";
	}

}
///////////////////////////////////////////Main///////////////////////////////////////////////////////////////
/*
 * Caso de estudio: Ocho loco
 * Repaso del encoque orientado a objetos
 * Taller1
 * Curso de PI
 * EISC Univalle
 * Juan Felipe Alvarado(1745283)
 * Daniel Bermudez (1742658)
 */

package ochoLoco;

public class Main {

	public static void m/*
 * Caso de estudio: Ocho loco
 * Repaso del encoque orientado a objetos
 * Taller1
 * Curso de PI
 * EISC Univalle
 * Juan Felipe Alvarado(1745283)
 * Daniel Bermudez (1742658)
 */

package ochoLoco;

public class VistaConsola {

}
ain(String[] args) {
		// TODO Auto-generated method stub

	}

}
/////////////////////////////////////////VistaConsola.java///////////////////////////////////////////
/*
 * Caso de estudio: Ocho loco
 * Repaso del encoque orientado a objetos
 * Taller1
 * Curso de PI
 * EISC Univalle
 * Juan Felipe Alvarado(1745283)
 * Daniel Bermudez (1742658)
 */

package ochoLoco;

public class VistaConsola {

}
