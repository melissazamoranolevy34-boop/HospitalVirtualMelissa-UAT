# CU001 Admisión de Paciente

## Objetivo

Registrar un paciente en el sistema.

## Flujo

1. Paciente llega al hospital.
2. Se valida RUN.
3. Se crea registro del paciente.
4. Se genera episodio de atención.
5. Se genera mensaje HL7 ADT A01.
6. El paciente queda disponible para atención clínica.

## Resultado Esperado

Paciente registrado correctamente y mensaje ADT A01 generado.
## Mensajes Asociados

- HL7 ADT A01

## Recursos FHIR Asociados

- Patient

## Casos de Prueba Asociados

- TC001_Admision
