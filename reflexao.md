# Reflexão

## 1. O que exatamente causou o conflito?
O conflito aconteceu porque as duas pessoas alteraram a mesma linha do mesmo arquivo (`README.md`) em versões diferentes, sem que uma tivesse recebido a alteração da outra antes de fazer o commit.

## 2. Como vocês decidiram qual versão manter?
Para resolver, comparamos as duas versões e decidimos mesclar as alterações e criar uma versão que fazia mais sentido para o projeto, removendo os marcadores de conflito adicionados pelo Git.

## 3. Se isso acontecesse num projeto real com várias pessoas mexendo no mesmo arquivo o tempo todo, o que vocês fariam diferente para evitar conflitos?
Em um projeto real, evitaríamos conflitos fazendo `pull` com frequência, trabalhando em branches separadas para cada funcionalidade e fazendo commits menores e mais específicos. Também seria importante comunicar quais arquivos estão sendo alterados para evitar que várias pessoas modifiquem a mesma parte ao mesmo tempo.
