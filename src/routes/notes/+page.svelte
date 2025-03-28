<script>
    import NoteEl from "$lib/NoteEl.svelte";
    import NotesSection from "$lib/NotesSection.svelte";
</script>

<h1 class="text-3xl font-bold">Primer Año</h1>
<NotesSection title="Primer Cuatrimestre">
    <NoteEl title="Álgebra Lineal" href="" color="bg-aurora-red"/>
    <NoteEl title="Aproximación Numérica" href="" color="bg-aurora-green"/>
    <NoteEl title="Cálculo en una variable" href="" color="bg-aurora-yellow"/>
    <NoteEl title="Estadística Descriptiva e Inferencial" href="" color="bg-aurora-pink"/>
    <NoteEl title="Física I" href="" color="bg-aurora-orange"/>
    <NoteEl title="Introducción a la programación" href="" color="bg-third"/>
</NotesSection>
<NotesSection title="Segundo Cuatrimestre">
    <NoteEl title="Cálculo en varias variables" href="" color="bg-aurora-pink"/>
    <NoteEl title="Geometría Proyectiva" href="" color="bg-aurora-red"/>
    <NoteEl title="Física II" href="" color="bg-aurora-yellow"/>
    <NoteEl title="Matemática Probabilística" href="" color="bg-aurora-green"/>
    <NoteEl title="Topología Elemental" href="" color="bg-third"/>
    <NoteEl title="Programación Avanzada" href="" color="bg-aurora-orange"/>
</NotesSection>