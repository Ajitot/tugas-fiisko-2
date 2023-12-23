{
  "cells": [
    {
      "cell_type": "markdown",
      "source": [
        "Sebuah bola mula-mula dalam keadaan diam pada lantai yang licin, kemudian bola didorong sehingga mengalami percepatan sebesar $4 m/s^2$, tentukan kecepatan bola setelah bergerak selama 8 sekon!\n",
        "\n",
        "Diketahui \\\n",
        "$V_0 = 0 m/s$ \\\n",
        "$a = 4m/s$ \\\n",
        "$t = 8 m/s$ \\\n",
        "$V_t = ?$ \\\n",
        "\n",
        "\n"
      ],
      "metadata": {
        "id": "rRhQ07VgR4Sq"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "* Percepatan konstan didefinisikan sebagai perubahan kecepatan terhadap waktu ; \\\n",
        "$a = \\frac{dv}{dt}$ \\\n",
        "$a.dt = dv_{(t)}$ \\\n",
        "$a \\int dt = \\int dv_{(t)}$ \\\n",
        "$at = v_{(t)} + c$ \\\n",
        "$c = -v_{(0)}$ \\\n",
        "\n",
        "* Jika dimisalkan waktu adalah 0 maka \\\n",
        "$v_{(t)} = v_{(0)} + at$ \\\n",
        "$\\frac{ds_{(t)}}{dt} = v{(0)} + at$ \\\n",
        "$\\int ds_{(t)} = v_{(0)} \\int dt + a \\int t.dt$ \\\n",
        "$s_{(t)} = v_{(0)}t + \\frac{1}{2} at^2 + c$\n",
        "\n",
        "\n",
        "\n",
        "\n",
        "\n",
        "\n"
      ],
      "metadata": {
        "id": "ee7Ba2XC_dT9"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "# v_t = v_0 + a*t\n",
        "v_0 = 0\n",
        "a = 9\n",
        "t = 10\n",
        "\n",
        "v_t = v_0 + a*t\n",
        "print(v_t, \"m/s\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "v0x6N6mCExFn",
        "outputId": "52ceb9c9-52c5-4271-f6e5-68ef782cbe64"
      },
      "execution_count": 2,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "90 m/s\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#"
      ],
      "metadata": {
        "id": "bu5n373EFtON"
      },
      "execution_count": null,
      "outputs": []
    }
  ],
  "metadata": {
    "colab": {
      "provenance": []
    },
    "kernelspec": {
      "display_name": "Python 3",
      "name": "python3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "nbformat": 4,
  "nbformat_minor": 0
}
