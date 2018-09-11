# OchoLoco
OchoLoco Cartas
////////////////////Carta.java///////////////////////
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

import java.util.Random;
import java.util.ArrayList;

public class Carta {
	/*
	 * ArrayList<String> nombreArrayList = new ArrayList<String>();
	 * 
	 * 
	
	public Carta()
	{
		
	}
	
	String[] Palo = {"P", "C", "T", "D"};
	
	String[] Numero = {"A", "2", "3", "4", "5", "6", "7", "8", "9", "10", "J", "Q", "K"};
	*/
	
	ArrayList<String> mazo = new ArrayList<String>();
	
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
	String figura="";
	String numeros="";
	public String cartaRandom()
	{
		for(int palo=0; palo<=3; palo++)
		{
			if (palo==0)
			{
				figura="D";
			}
			else 
				if (palo==1)
				{
					figura="T";
				}
				else 
					if (palo==2)
					{
						figura="C";
					}
					else 
						if (palo==3)
						{
							figura="P";
						}
			for (int numero=1; numero<=13; numero++)
			{
				numeros=String.valueOf(numero);
				if (numero==1)
				{
					mazo.add(figura+"A");
				}
				else
					if (numero==10)
					{
						mazo.add(figura+"J");
					}
					else 
						if (numero==11)
						{
							mazo.add(figura+"Q");
						}
						else
							if (numero==12)
							{
								mazo.add(figura+"K");
							}
							else
							{
								mazo.add(figura+numeros);
							}
			}
		}
	return auxCarta;
	}
	String auxCarta;
/*	public void cartaRandom()
	{
		Random randomPrincipal = new Random();
		int paloRandom = randomPrincipal.nextInt(3);
		int numeroRandom= randomPrincipal.nextInt(12);
		String cartaEnJuego = Palo[paloRandom] + Numero[numeroRandom];
		//return Numero[numeroRandom] + " de " + Palo[paloRandom];
	}
*/
	
	public void cartaRepetida()
	{
		if()
	}
	public String armaMazo()
	{
		//auxCarta=cartaRandom();
		for(int i=0; i<=51; i++)
		{
			mazo.add(i, cartaRandom());
			if (mazo.get(i))
		}
		return 
	}
	
	public void repartirCartas()
	{
		
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
