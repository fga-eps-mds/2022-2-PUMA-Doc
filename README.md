# PUMA - Plataforma Unificada de Metodologias Ativas

Repositório para documentação do projeto PUMA, desenvolvido pelos membros das disciplinas Metódos de Desenvolvimento de Software (MDS) e Engenharia do Produto de Software (EPS).

## Repositórios de Implementação

[Deploy](https://github.com/fga-eps-mds/2022-2-PUMA-Deploy)

[Front-end](https://github.com/fga-eps-mds/2022-2-PUMA-Frontend)

[Api Gateway](https://github.com/fga-eps-mds/2022-2-PUMA-ApiGateway)

[User Service](https://github.com/fga-eps-mds/2022-2-PUMA-UserService)

[Project Service](https://github.com/fga-eps-mds/2022-2-PUMA-ProjectService)

[Alocate Service](https://github.com/fga-eps-mds/2022-2-PUMA-AlocateService)

[Notify Service](https://github.com/fga-eps-mds/2022-2-PUMA-NotifyService)

## Time

**Nome** | **Matricula** | **GitHub**
---------|:-------------:|:----------:
Ailamar Alves Guimarães | 160022673 | ailamaralves
Marcelo Araújo dos Santos | 160035481 | marcelo046
Hérya Rodrigues Alcantara | 180018574 | hryds
Nilo Mendonça de Brito Júnior | 160037522 | NiloMendonca
Giovana Vitor Dionisio Santana | 180017659 | giovanadionisio
Matheus Amaral Moreira | 170080307 | Matheus-AM
Débora Cairess | 222015103 | deboracaires   
Gabriel Marques de Souza | 202016266 | GabrielMS00
Felipe Nunes de Mello | 202023647 | Felipe NunesdM
Cainã Valença de Freitas | 180014412 | freitasc
Endy Sally Soares Andrade | 180113194 | EndySally


## GitHub Pages - Desenvolvimento Local

### Dependências

Virtualenv:
```console
pip3 install virtualenv
```

### Preparando Ambiente e Subindo Servidor

No diretório raiz do repositório, crie o ambiente:
```console
virtualenv -p python3 env
```

Ative o ambiente:

```console
source env/bin/activate
```

Instale o Material mkdocs:
```console
pip3 install mkdocs-material
```

Inicie o servidor de desenvolvimento:
```console
mkdocs serve
```

## PUMA - Desenvolvimento Local

1. Crie uma pasta para armazenar os repositórios do projeto.

2. Insira os [scripts](https://drive.google.com/drive/folders/11_sBJonAoB_wbzEFLuyG1D0dMOTSvECL?usp=sharing) dentro da pasta criada.

3. Insira a [pasta envs](https://drive.google.com/drive/folders/1bCZ2RPNPU7U_vFwq6A_C2P2FjUKI3q92?usp=sharing) dentro da pasta criada.

4. Recupere o IP da sua máquina(ifconfig) e insira nas variáveis de IP dos .envs que estão dentro da pasta envs.

5. Entre na pasta criada a partir do terminal.

6. Clone os repositórios do projeto:
   - Via ssh:
        ```console
        source clone_repos_ssh.sh
        ```

   - Via http:
        ```console
        source clone_repos_http.sh
        ```

7. Utilize o script move_envs.sh para mover todos os .envs para os seus respectivos repositórios.
    ```console
    source move_envs.sh
    ```

8. Entre no repositório Api-Gateway e execute:
    ```console
    make up-build
    ```

9. Após subir todos os containers com _make up-build_, abra outro terminal na pasta criada na etapa 1 e popule o banco de dados da aplicação:
    ```console
    source db_script.sh populate
    ```

10.   Pronto ! Agora é só acessar http://localhost:8080/
