# Ein Bespiel, um ein jar in einem Docker-Image unter OpenShift zum Laufen zu bringen

    # Projekt anlegen
    $ oc new-project mysample

    # ImageStream anlegen
    $ oc create -f imagestream.yml

    # Build anlegen
    $ oc create -f build.yml

    # Build starten
    $ oc start-build sample-build  --from-dir=.

    # Add Project -> Deploy Image
