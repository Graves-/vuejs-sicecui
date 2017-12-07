<template>
    <div class="InscripcionAlumno container">
        <div class="row">
            <div class="col-xl-4 col-lg-4 col-md-4 col-sm-12 col-xs-12">
                <label for="Nombre">Nombre:</label>
                <input name="Nombre" class="form-control" placeholder="Nombre">
            </div>
            <div class="col-xl-4 col-lg-4 col-md-4 col-sm-12 col-xs-12">
                <label for="Paterno">Apellido paterno:</label>
                <input name="Paterno" class="form-control" placeholder="Apellido Paterno">
            </div>
            <div class="col-xl-4 col-lg-4 col-md-4 col-sm-12 col-xs-12">
                <label for="Materno">Apellido Materno:</label>
                <input name="Materno" class="form-control" placeholder="Apellido Materno">
            </div>
        </div>

        <div class="row">
            <div class="col-xl-12 col-lg-12 col-md-12 col-sm-12 col-xs-12">
                <label for="Carrera">Carrera:</label>
                <select class="form-control" name="Carrera" id="selectCarrera">
                    <option value="">Selecciona una carrera</option>
                    <option value="LEA">Licenciatura en Administración</option>
                    <option value="LEI">Licenciatura en Informática</option>
                    <option value="LED">Licenciatura en Derecho</option>
                    <option value="LEC">Licenciatura en Contablidad</option>
                </select>
            </div>
        </div>

        <div class="row">

        </div>

    </div>
</template>

<script>
import VueAutocompete from './autocomplete'
export default {
    name: 'InscripcionAlumno',
    components: { VueAutocompete },
    data(){
        return{
            
        }
    },
    created(){
        console.log('created')
    }
}
</script>

<style>

</style>
