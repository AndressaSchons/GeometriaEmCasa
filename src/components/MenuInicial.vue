<template>
     <div class="container text-center backg">
            <div class="row">
                <div class="col">
                    <!--BOTAO VOLTAR-->
                    <button type="submit" class="btn btn-primary">VOLTAR</button>
                </div>
                <div class="col-8 aa" >
                    <img src="./images/placa.png" alt="Placa de madeira" id="placa">
                    <div class="forms">
                        <p>OLÁ!</p>
                        <form>
                            <div class="mb-3">
                            <label for="exampleInputEmail1" class="form-label">INSIRA SEU NOME:</label>
                            <input class="form-control" type="text" placeholder="INSIRA SEU NOME" aria-label="default input example">
                            </div>
                            
                        </form>
                    </div>
                </div>
                <div class="col">
                    <button type="submit" class="btn btn-primary">CONTINUAR</button>
                    <!--BOTAO CONTINUAR-->
                </div> 
            </div>
        </div>
</template>
<style scoped>

#placa{
position: relative;
    width: 440px;
    height: 370px;
}

.forms{
    position: absolute;
}

.aa{
    display: flex;
    justify-content: center;
    text-align: center;
}

</style>