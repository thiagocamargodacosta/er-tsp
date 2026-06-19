# er-tsp

er-tsp is a dataset with the localities that belong to the Estrada Real developed during the Master of Science in Computer Science program at UFOP. The goal is to provide TSP instances - of a historical and tourist route - that can be used in simulations.

## Contributors

**Developed by**
> Thiago Camargo Da Costa
> 
> MSc candidate at the Post-graduate program in Computer Science of the Federal University of Ouro Preto (UFOP)
> 
> [Lattes](https://lattes.cnpq.br/7279342712905776) | [Email](mailto:thiago.camargo@aluno.ufop.edu.br)

**Advisor**
> André Luiz Carvalho Ottoni
> 
> Professor at the Computing Deparment (DECOM) of the Federal University of Ouro Preto (UFOP)
> 
> [Lattes](http://lattes.cnpq.br/2003401420560517)

## About the dataset

Comprised of 5 routes (instances):
- Sabarabuçu $n = 12$
- Diamantes $n = 67$
- Novo $n = 79$
- Velho $n = 105$
- Completo $n = 247$

`${sabarabucu,diamantes,novo,velho,completo}-utm-x-y.txt` contain the UTM coordinates of each location (sorted alphabetically based on the location name). The coordinates used were obtained through the locality's listing available in the [instituto estrada real](https://institutoestradareal.com.br/) webpage.

`${sabarabucu,diamantes,novo,velho,completo}-wgs84-long-lat.txt` contain the WGS84 coordinates of each location (sorted alphabetically based on the location name). The coordinates used were obtained through the locality's listing available in the [instituto estrada real](https://institutoestradareal.com.br/) webpage.

`localidade-url-${sabarabucu,diamantes,novo,velho,completo}.csv` contain the name of the locality, URL used to retrieve the coordinates, and the instance's (caminho) name.

## Published article

An article using this instance was published in the LVII Operations Research Brazilian Symposium (SBPO) in 2025.

'''
@inproceedings{costa_aprendizado_2025,
	title = {Aprendizado por {Reforço} {Automatizado} no {Planejamento} de {Rotas} de {Turismo} da {Estrada} {Real}},
	url = {https://proceedings.science/proceedings/100607/_papers/212424},
	doi = {10.59254/sbpo-2025-212424},
	urldate = {2026-06-19},
	author = {Costa, Thiago Camargo Da and Santos, Samara Oliveira Silva and Nepomuceno, Erivelton Geraldo and Ottoni, André Luiz Carvalho},
	year = {2025},
}
'''

doi:[10.59254/sbpo-2025-212424](doi.org/10.59254/sbpo-2025-212424)
