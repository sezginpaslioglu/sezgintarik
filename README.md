# sezgintarik{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Zaman Serilerinde Anomali Tespiti\n",
    "\n",
    "## Members\n",
    "\n",
    "1. First member: Tarık Yıldırımlı / yildirimlit@itu.edu.tr\n",
    "2. Second member: Sezgin Paslıoğlu / paslioglu@itu.edu.tr\n",
    "\n",
    "## Description of the project\n",
    "\n",
    "### The methods to be used\n",
    "\n",
    "R\n",
    "\n",
    "### The data\n",
    "\n",
    "https://data.bls.gov/timeseries/LNU04000000\n",
    "\n",
    "## Code\n",
    "\n",
    "As proof of work, you must run this notebook.  Upload an HTML output of this notebook on your github account."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": false
   },
   "outputs": [],
   "source": [
    "data <- read.csv(\"https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data\", header=FALSE)\n",
    "head(data)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {
    "collapsed": false
   },
   "outputs": [],
   "source": [
    "hist(data$V4)"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "R",
   "language": "R",
   "name": "ir"
  },
  "language_info": {
   "codemirror_mode": "r",
   "file_extension": ".r",
   "mimetype": "text/x-r-source",
   "name": "R",
   "pygments_lexer": "r",
   "version": "3.2.3"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
