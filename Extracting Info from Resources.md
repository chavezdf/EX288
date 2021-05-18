
Extraer en formato JSON:

    oc get <type> -n namespace -o json
    
    oc get <resource> -n <namespace> -o jsonpath='{.status.availableReplicas}'
    
    **-o jsonpath** es para mostrar la info en un arbol de json. Se define la ruta que se desea imprimir.
