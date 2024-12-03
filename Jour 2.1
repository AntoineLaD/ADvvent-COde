#include <stdio.h>

int est_croissant(int liste[1000][8], int ligne, int taille) {
	for(int i = 0; i < taille - 1 ; i++ ) {
		if (liste[ligne][i+1]== 0) {
			break;
		}
		if(liste[ligne][i] > liste[ligne][i+1] ) {
			return 0;
		}


	}
	return 1;

}

int est_decroissant(int liste[1000][8], int ligne, int taille) {
	for(int i = 0; i < taille - 1 ; i++ ) {
		if (liste[ligne][i+1]== 0) {
			break;
		}
		if(liste[ligne][i] < liste[ligne][i+1] ) {
			return 0;
		}


	}
	return 1;

}


int est_fonction (int liste[1000][8], int ligne, int taille) {
	if(est_decroissant(liste,ligne,taille)==1) {
		return 1;
	}
	else if ( est_croissant(liste, ligne, taille) == 1) {
		return 1;
	}
	else {
		return 0;
	}
}

void fonction(int liste[1000][8]) {

	int total=0;

	for (int i = 0; i < 1000; i++) {

		int j = 0;
		int compteur1 = 0;

		while ( liste[i][j] != 0 && j < 8 -1 ) {
			int var = liste[i][j] - liste[i][j+1];
			if ( var != 0 && (est_fonction(liste,i,8) != 0 )) {
				if( -3 <= var && var <= 3 && var != 0) {
					compteur1++;

				}
			     if( (var <= -3 || var >=3) && liste[i][j+1]==0){
				    compteur1++;
				}
			}

			j++;


		}
		if (compteur1 == j) {
			total ++;
			printf("+1 pour %d",i);


		}

	}
	printf("total final: %d  ,",total);
}


int main() {
	int liste[1000][8]= {0};
	int list[6][5]= {{7, 5, 4, 0, 0},
		{1, 2, 7, 8, 9},
		{9, 7, 6, 2, 1},
		{1, 3, 2, 4, 5},
		{8, 6, 4, 3, 1},
		{1, 3, 6, 7, 9}
	};

    //	fonction(list);

	int i = 0;

	FILE * file;
	file = fopen("adventofcode.txt","r");
	while (i < 1000) {
		int j = 0;
		while (j < 8) {
			if (fscanf(file, "%d", &liste[i][j]) == 1) {

			}
			if(fgetc(file) == '\n') {
				j = 8;

			}
			j++;



		}



		i++;
	}


	for(int i = 0; i < 1000; i++) {
		for(int j = 0; j < 8; j++) {
			printf("%d ",liste[i][j]);
		}
		printf("\n");
	}



	fclose(file);

	//fonction(list);
	fonction (liste);



}
