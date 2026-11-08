# Chatbot IA pour WhatsApp

Un chatbot intelligent développé avec **n8n**, **WhatsApp Cloud API** et **Google Gemini**. Ce projet permet d'automatiser les échanges sur WhatsApp grâce à l'intelligence artificielle.

## Démonstration vidéo

https://youtu.be/p3JYcFQb2-g

## Technologies utilisées

- **n8n** : automatisation du workflow et gestion de l'agent IA.
- **Google Gemini** : génération des réponses intelligentes.
- **WhatsApp Cloud API** : réception et envoi des messages.
- **PostgreSQL Chat Memory** : conservation du contexte des conversations.
- **Docker** : hébergement local de l'instance n8n.
- **Cloudflare Tunnel** : accès externe aux webhooks.

## Fonctionnalités

- Réception et traitement automatique des messages WhatsApp.
- Génération de réponses grâce à Google Gemini.
- Mémoire conversationnelle.
- Prise en charge de plusieurs langues.
- Exécution manuelle et automatique du workflow.

## Fonctionnement

1. Un utilisateur envoie un message sur WhatsApp.
2. Le nœud WhatsApp Trigger reçoit le message.
3. L'agent IA analyse la demande avec Google Gemini.
4. La mémoire conversationnelle fournit le contexte nécessaire.
5. La réponse générée est envoyée directement sur WhatsApp.

## Hébergement

L'instance **n8n est hébergée localement sur une machine à l'aide de Docker**. Cloudflare Tunnel permet d'exposer les webhooks nécessaires à la communication avec WhatsApp Cloud API.

## Objectif du projet

Concevoir un assistant conversationnel automatisé capable de comprendre les messages des utilisateurs et de leur répondre en temps réel grâce à l'intelligence artificielle.
