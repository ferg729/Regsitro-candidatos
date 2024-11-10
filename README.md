# Registro-candidatos
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registro de Candidatos</title>
</head>
<body>
    <form action="https://your-ats-platform.com/api/submit" method="POST">
        <h3>Información Personal</h3>
        <label for="nombre">Nombre Completo:</label>
        <input type="text" id="nombre" name="nombre" required>
        
        <label for="email">Correo Electrónico:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="telefono">Número de Teléfono:</label>
        <input type="tel" id="telefono" name="telefono" required>
        
        <label for="pais">País de Residencia:</label>
        <input type="text" id="pais" name="pais" required>
        
        <h3>Información Profesional</h3>
        <label for="puesto">Puesto Deseado:</label>
        <input type="text" id="puesto" name="puesto" required>
        
        <label for="experiencia">Experiencia Laboral (en años):</label>
        <input type="number" id="experiencia" name="experiencia" required>
        
        <label for="educacion">Nivel Educativo:</label>
        <input type="text" id="educacion" name="educacion" required>
        
        <label for="idiomas">Idiomas Hablados:</label>
        <input type="text" id="idiomas" name="idiomas" required>
        
        <label for="reubicacion">Disponibilidad para Reubicarse:</label>
        <select id="reubicacion" name="reubicacion">
            <option value="si">Sí</option>
            <option value="no">No</option>
        </select>
        
        <label for="curriculum">Currículum (archivo adjunto):</label>
        <input type="file" id="curriculum" name="curriculum" required>
        
        <h3>Habilidades y Competencias</h3>
        <label for="habilidades_tecnicas">Habilidades Técnicas:</label>
        <input type="text" id="habilidades_tecnicas" name="habilidades_tecnicas" required>
        
        <label for="habilidades_blandas">Habilidades Blandas:</label>
        <input type="text" id="habilidades_blandas" name="habilidades_blandas" required>
        
        <label for="certificaciones">Certificaciones (archivo adjunto):</label>
        <input type="file" id="certificaciones" name="certificaciones">
        
        <label for="proyectos">Proyectos Relevantes (opcional):</label>
        <textarea id="proyectos" name="proyectos"></textarea>
        
        <h3>Otros</h3>
        <label for="salario">Expectativas Salariales:</label>
        <input type="text" id="salario" name="salario" required>
        
        <label for="disponibilidad">Disponibilidad para Comenzar:</label>
        <input type="date" id="disponibilidad" name="disponibilidad" required>
        
        <label for="referencias">Referencias:</label>
        <textarea id="referencias" name="referencias"></textarea>
        
        <label for="comentarios">Comentarios Adicionales:</label>
        <textarea id="comentarios" name="comentarios"></textarea>
        
        <button type="submit">Enviar</button>
    </form>
</body>
</html>
