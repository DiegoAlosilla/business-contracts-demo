# Contratos Business de demostración

Veinte contratos OpenAPI 3.1 ficticios para el [asistente de diseño de canal](https://github.com/DiegoAlosilla/backend-java-hackathon). Cubren solicitudes, evaluación crediticia, simulación, confirmación, desembolso y capacidades relacionadas. Son documentos de ejemplo sin servidores ni datos bancarios reales.

## Catálogo

- [business-customer-lead-v2](contracts/business-customer-lead-v2.openapi.json) · `GET /customers/{cxi}/leads` · Consultar prospectos comerciales del cliente
- [business-person-v5](contracts/business-person-v5.openapi.json) · `GET /people/{cxi}` · Recuperar perfil del cliente por CXI
- [business-credit-assessment-v1](contracts/business-credit-assessment-v1.openapi.json) · `POST /credit-assessments` · Evaluar riesgo crediticio del solicitante
- [business-loan-application-v1](contracts/business-loan-application-v1.openapi.json) · `POST /loan-applications` · Registrar e iniciar una solicitud de préstamo personal
- [business-loan-simulation-v2](contracts/business-loan-simulation-v2.openapi.json) · `POST /loan-simulations` · Simular cuota, tasa y plazo de un préstamo evaluado
- [business-loan-confirmation-v1](contracts/business-loan-confirmation-v1.openapi.json) · `POST /loan-applications/{applicationId}/confirmations` · Confirmar datos y aceptación de una simulación de préstamo
- [business-loan-disbursement-v2](contracts/business-loan-disbursement-v2.openapi.json) · `POST /loan-applications/{applicationId}/disbursements` · Ejecutar desembolso de préstamo confirmado
- [business-customer-offer-v2](contracts/business-customer-offer-v2.openapi.json) · `GET /customers/{cxi}/offers` · Consultar ofertas vigentes del cliente
- [business-account-ownership-v1](contracts/business-account-ownership-v1.openapi.json) · `GET /accounts/{accountId}/ownership` · Consultar titularidad y vigencia de la cuenta de abono
- [business-customer-consent-v1](contracts/business-customer-consent-v1.openapi.json) · `POST /customer-consents` · Registrar consentimiento del cliente
- [business-identity-verification-v2](contracts/business-identity-verification-v2.openapi.json) · `POST /identity-verifications` · Verificar identidad declarada del cliente
- [business-risk-profile-v3](contracts/business-risk-profile-v3.openapi.json) · `GET /customers/{cxi}/risk-profile` · Consultar perfil de riesgo vigente
- [business-income-verification-v1](contracts/business-income-verification-v1.openapi.json) · `POST /income-verifications` · Evaluar ingresos declarados del solicitante
- [business-product-pricing-v2](contracts/business-product-pricing-v2.openapi.json) · `GET /products/{productId}/rates` · Consultar tasas y comisiones por producto
- [business-loan-eligibility-v1](contracts/business-loan-eligibility-v1.openapi.json) · `GET /customers/{cxi}/loan-eligibility` · Consultar elegibilidad preliminar para préstamos
- [business-document-registry-v1](contracts/business-document-registry-v1.openapi.json) · `GET /customers/{cxi}/documents` · Recuperar metadatos de documentos del cliente
- [business-fraud-screening-v2](contracts/business-fraud-screening-v2.openapi.json) · `POST /fraud-screenings` · Evaluar señales de fraude para una solicitud
- [business-disbursement-status-v1](contracts/business-disbursement-status-v1.openapi.json) · `GET /disbursements/{disbursementId}` · Consultar estado de un desembolso existente
- [business-payment-schedule-v1](contracts/business-payment-schedule-v1.openapi.json) · `GET /loans/{loanId}/payment-schedule` · Consultar cronograma del préstamo desembolsado
- [business-notification-v2](contracts/business-notification-v2.openapi.json) · `POST /notifications` · Solicitar notificación transaccional al cliente
