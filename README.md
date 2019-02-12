# ArrayList
Matriz de Valores Pares e Impares

package com.exercicios;

import java.util.ArrayList;

public class valoresImpares {

	public static void main(String[] args) {
		
		
		//Cria ArrayList
		ArrayList <Integer> contadorp = new ArrayList <Integer>();
		ArrayList <Integer> contadori = new ArrayList <Integer>();
		
		//Preenche a ArrayList
		for(int i = 1; i < 100; i++) {
			for(int j = i; j == i; j++) {
			contadorp.add(i);
			contadori.add(j);
		}
		}
		
		//lê arraylist e imprime se for impar
		for (int i : contadorp) {
			if ((i % 2 ) == 0)
				System.out.println("Par encontrado: " + i);
		}
		
		for (int j : contadori){
			if ((j % 2)!= 0)
			System.out.println("Impar encontrado: " + j);
		}
	}

}

