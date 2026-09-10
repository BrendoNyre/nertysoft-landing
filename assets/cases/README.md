# Mídia dos Cases

Cada pasta corresponde a um case da seção "Projetos Reais" do site. Para publicar
fotos e vídeos reais de um projeto, basta salvar os arquivos com esses nomes
exatos dentro da pasta do case — o site detecta sozinho quando o arquivo existe,
sem precisar mexer no `index.html`.

Convenção de arquivos por pasta (`lpr/`, `erp-oficina/`, `agendamento/`, `pdv/`):

| Arquivo       | Uso                                             | Recomendado        |
|---------------|--------------------------------------------------|---------------------|
| `capa.jpg`    | Foto/print de capa do case                       | 1200x675px (16:9)  |
| `video.mp4`   | Vídeo do projeto (demo ou depoimento do cliente) | H.264, até ~50MB   |
| `foto-2.jpg`  | Foto extra (miniatura clicável)                  | qualquer proporção |
| `foto-3.jpg`  | Foto extra (miniatura clicável)                  | qualquer proporção |
| `foto-4.jpg`  | Foto extra (miniatura clicável)                  | qualquer proporção |

Não é obrigatório ter todos os arquivos — o que faltar simplesmente não aparece
(sem imagem quebrada, sem botão de vídeo vazio).

Depoimentos escritos de clientes: descomente o bloco `<blockquote>` correspondente
dentro do `index.html`, no case desejado, e preencha com a frase real e o nome/cargo
do cliente.
