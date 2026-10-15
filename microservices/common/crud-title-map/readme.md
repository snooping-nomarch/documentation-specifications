# common-crud-title-map

Платформенный фрагмент OpenAPI с общими схемами batch `title-map` ([ADR-26062101](../../../../ADR/ADR-26062101-rest-title-map-batch.md)).

Содержимое [openapi.yaml](./openapi.yaml):

- [TitleMapRequest](./openapi.yaml#/components/schemas/TitleMapRequest)
- [TitleMapResponse](./openapi.yaml#/components/schemas/TitleMapResponse)
- [TitleMapItem](./openapi.yaml#/components/schemas/TitleMapItem)

CRUD-сервисы-владельцы подключают схемы через внешний `$ref`; генерация — shared Maven/npm артефакт (`openapi.codegen.yaml` → `sharedModels`).
