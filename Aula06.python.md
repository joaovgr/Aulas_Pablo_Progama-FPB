# Aulas_Pablo_Progama-FPB
Minhas aulas na FPB
{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "authorship_tag": "ABX9TyP3lvTXEGoEd/PQoVFHPOA4",
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/joaovgr/Aula_FPB_Demetruis/blob/main/Aula06Pablo_AppendWhile.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": 3,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "8XEol_EhsAb3",
        "outputId": "410de648-3627-407d-9f09-afc3400e61e7"
      },
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "faca\n",
            "irmão\n",
            "cachorro\n"
          ]
        }
      ],
      "source": [
        "#Usando o for\n",
        "\n",
        "obj = ['faca' ,'irmão' , 'cachorro']\n",
        "for i in obj:\n",
        "  print(i)"
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#Crie uma lista com 5 números em seguida\n",
        "\n",
        "nums = [1,2,3,4,5]\n",
        "nums.append(6)\n",
        "for i in nums:\n",
        "  print(i)\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "SPhvLCmAtElt",
        "outputId": "060e322f-db00-4557-8751-adf106c13f4a"
      },
      "execution_count": 5,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "1\n",
            "2\n",
            "3\n",
            "4\n",
            "5\n",
            "6\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#Range diz até onde o número vai\n",
        "\n",
        "range(15)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Umjo58BSubSE",
        "outputId": "544659b5-4fa5-4b9b-a1d0-86d07c4d4596"
      },
      "execution_count": 6,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "range(0, 15)"
            ]
          },
          "metadata": {},
          "execution_count": 6
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#Criar uma lista de 1 à 15\n",
        "nums = []\n",
        "for num in range(1,15):\n",
        "  print(num)\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "t18D3hHdtm8G",
        "outputId": "dbbe2da0-b82b-49e2-d2ca-7ecf672bced6"
      },
      "execution_count": 7,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "1\n",
            "2\n",
            "3\n",
            "4\n",
            "5\n",
            "6\n",
            "7\n",
            "8\n",
            "9\n",
            "10\n",
            "11\n",
            "12\n",
            "13\n",
            "14\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#Para usar  a biblioteca Radom, é preciso importála\n",
        "\n",
        "import random\n",
        "\n",
        "#Criar uma lista com o tamanho aleatório (Entre 0 e 50)\n",
        "\n",
        "nums1 = []\n",
        "for num in range(random.randrange(0,50)):\n",
        "  nums1.append(num)\n",
        "print(nums1)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "26gKlLKxwPNa",
        "outputId": "5860d39f-bc5c-41b5-d422-6acf95a08755"
      },
      "execution_count": 18,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#(Parentesis) Descobrir se um número é par\n",
        "\n",
        "num  = int(input(\"Digite o número: \"))\n",
        "\n",
        "if ( num % 2 == 0):\n",
        "  print()\n",
        "  print('O número e par!')\n",
        "else:\n",
        "  print()\n",
        "  print('O número é impar!')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "9RAo7gvhy5HG",
        "outputId": "76faebf3-2016-45e9-9c09-4e7b937ceb59"
      },
      "execution_count": 21,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite o número: 13\n",
            "\n",
            "O número é impar!\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#Printar os números pares de até 50)\n",
        "\n",
        "numpar = []\n",
        "for num in range(51):\n",
        " if (num % 2 == 0):\n",
        "  numpar.append(num)\n",
        "print(numpar)\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "v2ebdM2-0I1b",
        "outputId": "9d3ad026-4f16-4f0f-c9b6-aa6f4250df17"
      },
      "execution_count": 31,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[0, 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#Retorne as somas dos número de 1 à 100\n",
        "soma = 0\n",
        "for i in range(1,101):\n",
        " soma = soma + i\n",
        "print(soma)\n",
        " "
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "VU_FXR3I3a48",
        "outputId": "a3fc62f6-e4de-4148-b53c-820e8fcf628d"
      },
      "execution_count": 51,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "5050\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#Criar um progama que lista os números de 1 à 100\n",
        "#Precisamos de um contador\n",
        "\n",
        "n = 0\n",
        "while (n < 10):\n",
        " print(n + 1)\n",
        " n+=1"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "QjHImuGA8mp1",
        "outputId": "893289a2-2202-4879-c699-cf04a274b3fb"
      },
      "execution_count": 62,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "1\n",
            "2\n",
            "3\n",
            "4\n",
            "5\n",
            "6\n",
            "7\n",
            "8\n",
            "9\n",
            "10\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#Pede ao usário para inserir um número inteiro maior do que 1!\n",
        "#O progama deve imprimir todos os números até o número digitado!\n",
        "num = 0\n",
        "n = int(input('Digite o número seu babaca: '))\n",
        "while (num <= n):\n",
        " print(num + 1)\n",
        " num+=1"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Lq1q_2RA-rcg",
        "outputId": "fdd60c2e-2eb5-40b0-f5e8-3d68357a1d22"
      },
      "execution_count": 76,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite o número seu babaca: 13\n",
            "1\n",
            "2\n",
            "3\n",
            "4\n",
            "5\n",
            "6\n",
            "7\n",
            "8\n",
            "9\n",
            "10\n",
            "11\n",
            "12\n",
            "13\n",
            "14\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "\n",
        "#Crie uma lista de compras onde quando você digitar 0 essa lista para\n",
        "\n",
        "compraslist = []\n",
        "produto = input('Digite o que deseja comprar: ')\n",
        "\n",
        "while (produto != '0'):\n",
        " compraslist.append(produto)\n",
        " produto = input('Digite o que deseja comprar: ')\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "v9pSCXh2COKb",
        "outputId": "b75d6f52-5b92-40a8-e00e-7efdd7022f4c"
      },
      "execution_count": 89,
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Digite o que deseja comprar: arroz\n",
            "Digite o que deseja comprar: Macarrão\n",
            "Digite o que deseja comprar: Feijão\n",
            "Digite o que deseja comprar: Batata\n",
            "Digite o que deseja comprar: Frango\n",
            "Digite o que deseja comprar: Carne\n",
            "Digite o que deseja comprar: 0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#Uso do append\n",
        "#Enquanto não estiver na condição pedida o número volta para a condição"
      ],
      "metadata": {
        "id": "eXyksUhqFE1D"
      },
      "execution_count": null,
      "outputs": []
    }
  ]
}
