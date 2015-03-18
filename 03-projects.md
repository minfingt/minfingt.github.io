---
title: "Proyectos"
bg: green
color: white
fa-icon: github
type: "home-section"
order: 3
id: "projects"
---

<h2>
  <i class="fa fa-check"></i>
  <a href="https://github.com/minfingt/validators" target="_blank">Validators</a>
</h2>

Libreria que contiene rutinas de validación comunes: Validación de NIT, Validación de DPI, etc. ([Ir al proyecto](https://github.com/minfingt/validators)).

### Ejemplo corto de Validators

```csharp
var validator = new Minfin.Validators.NitValidator();
validator.IsValid("35263164"); // true
```
