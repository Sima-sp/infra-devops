# SIMA-SP · infraestrutura

Configuração para subir o SIMA-SP completo: MySQL, backend
([`backend-core`](https://github.com/Sima-sp/backend-core)) e serviço de IA
([`ml-service`](https://github.com/Sima-sp/ml-service)).

## Estado

Ainda vazio. O próximo passo é um `docker-compose.yml` que suba os três com um comando
(semana de 21 a 27/11 do plano até a banca), e depois a hospedagem com https.

## Como o grupo trabalha

- Ninguém envia direto para a `main`: cada mudança vai numa branch e entra por pull request.
- O merge é sempre *squash* e a branch é apagada depois.
- Senhas e chaves ficam no `.env`, que nunca vai para o git; o repositório guarda só o `.env.example`.
