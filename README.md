# 🗺️ Editor de Requisições GeoServer

Uma ferramenta web simples para decodificar, editar e depurar URLs de requisições de geoserviços do **GeoServer** (como WMS, WFS, WCS, etc.). 

---

## Funcionalidades

*   **Análise de URLs**: Detecta automaticamente problemas comuns na URL, como:
    *   Espaços em branco não codificados.
    *   Parâmetros duplicados.
    *   Parâmetros sem valor definido.
    *   Segmentos vazios de query strings (`&` soltos).
*   **Edição do Caminho**: O caminho do servidor (ex: `/geoserver/workspace/ows`) é quebrado em segmentos editáveis diretamente no painel de status, permitindo ajustar a URL base rapidamente.
*   **Painel de Parâmetros**:
    *   **Ativação/Desativação Individual**: Remova parâmetros temporariamente da URL gerada sem perder o conteúdo digitado.
    *   **Edição Bidirecional**: Altere os valores na tabela e veja a URL da barra superior ser atualizada em tempo real, ou edite a URL diretamente para atualizar os campos.
    *   **Valores Multi-segmentados**: Detecta listas separadas por vírgulas (ex: `LAYERS=workspace:layer1,workspace:layer2`) e gera campos específicos para você editar, adicionar ou excluir sub-elementos individualmente.
*   **Codificação/Decodificação Rápida**: Alterne entre a versão codificada (`encodeURIComponent`) para requisições na web e a versão decodificada legível para humanos.
*   **Integração com Área de Transferência**: Copie a URL gerada ou cole uma URL com botões de atalho.

## Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes.
