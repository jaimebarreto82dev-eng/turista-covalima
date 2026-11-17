# Turista Cova-Lima

Landing page estática do projeto académico Turista Cova-Lima (2026), desenvolvido por Jaime Barreto no Institute of Business (IOB), Timor-Leste. Apresenta a aplicação Android e o sistema Web Admin do projeto.

## Pré-visualização local

Na raiz do repositório:

```bash
python3 -m http.server 8000
```

Abra `http://localhost:8000/`. Não há dependências ou etapa de build. Os caminhos dos assets são relativos para funcionar sob `/turista-covalima/` no GitHub Pages.

## Imagens reais pendentes

Atualmente só existe o favicon. Os espaços reservados do site estão identificados como tal. Coloque os ficheiros reais nestes locais:

| Tipo | Caminho esperado |
| --- | --- |
| Login Android | `assets/images/screenshots/android-login.png` |
| Home Screen | `assets/images/screenshots/android-home.png` |
| Lista Fatin Turizmu | `assets/images/screenshots/android-lista.png` |
| Detallu Fatin Turizmu | `assets/images/screenshots/android-detallu.png` |
| Mapa no Rota | `assets/images/screenshots/android-mapa.png` |
| Akomodasaun | `assets/images/screenshots/android-akomodasaun.png` |
| Merkadu | `assets/images/screenshots/android-merkadu.png` |
| Lian Haat | `assets/images/screenshots/android-lian.png` |
| Login Web Admin | `assets/images/screenshots/admin-login.png` |
| Dashboard Web Admin | `assets/images/screenshots/admin-dashboard.png` |
| Retrato formal | `assets/images/developer/jaime-profile.jpg` |
| Demonstração da aplicação | `assets/images/developer/jaime-app-demo.jpg` |

Quando os ficheiros com estes nomes forem adicionados, o JavaScript carrega-os automaticamente e substitui os placeholders. Capturas Android e Web Admin podem ser ampliadas com clique, Enter ou Espaço; Escape fecha a imagem e devolve o foco. As imagens fora do ecrã são carregadas à medida que o utilizador se aproxima delas. A captura `android-home.png` também aparece no hero.

Não publique capturas que mostrem credenciais ou dados privados. Preserve as proporções originais; para desempenho, use cópias otimizadas quando apropriado. A ilustração de natureza do hero permanece conceitual e está identificada como tal.

## SEO e publicação

`sitemap.xml` aponta para a página pública. Um `robots.txt` dentro de um projeto GitHub Pages é acessível pelo caminho do projeto, mas os motores de busca consultam normalmente apenas o `robots.txt` na raiz do domínio; o sitemap pode ser submetido diretamente no Search Console.

O ficheiro `google68fa8fba2040a4d4.html` deve permanecer intacto. O APK é distribuído pelo link Google Drive em `index.html`; não há listagem na Play Store. `index.html.backup` e `.aws` são ficheiros não rastreados fora do escopo; não os adicione ao Git.

Para rever alterações localmente:

```bash
git status --short
git diff --check
git diff -- index.html README.md
```

Faça commit, push e publicação apenas após aprovação explícita.
