**DeriveJS** simply seeks to find different ways of expressing JavaScript, if you have any Ideas, please make PR!

        {
        "undefined": [
            "void 0",
            "[]['']"
        ],
        "false": [
            "![]",
            "!{}",
            "!!''",
            "!!\"\""
        ],
        "true": [
            "!![]",
            "!!{}",
            "!''",
            "!\"\""
        ],
        "NaN": [
            "+{}",
            "0/0",
        ],
        "Infinity": [
            "1/0",
            "-Math.log(0)"
        ]
    }

