# aula
 const [incremento, setIncremento] = useState(0);

    let handlerClickAdicionar = () => {
        setIncremento(incremento + 1);
    };

    let handlerClickRemover = () => {
        setIncremento(incremento - 1);

        };
  return (
    <>
      <Header/>

      <p>{incremento}</p>
            
            <Button className="m-2" onClick={handlerClickAdicionar} variant="primary">
                Adicionar
            </Button>

            <Button className="m-2" onClick={handlerClickRemover} variant="danger">
                Remover
            </Button>
    </>
