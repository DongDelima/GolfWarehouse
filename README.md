Golf Warehouse ASP.NET Core API Clean Architecture + DDD
--------------------------------------------
This package includes:
- Domain: PsDoc, PsDocLin domain entities.
- Application: PosService that persists transactions via UnitOfWork.
- Infrastructure: EF Core DbContext, entity mappings for PS_DOC and PS_DOC_LIN (composite PK),
  repositories, UnitOfWork implementation.
- Api: Controller, Startup, Swagger enabled.
- Tests: xUnit test using FakeItEasy.
- SQL: create USER_SUGGESTED_REPLENISHMENT and trigger on PS_DOC_LIN.
-Use swagger or Postman

